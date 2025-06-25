# IT-Watchdogs Weathergoose RESTful Sensor for Home Assistant 
Integrate IT Watchdogs Weathergoose (WxGoos) sensor data into Home Assistant

The IT Watchdogs Weathergoose (WxGoos) helpfully outputs all it's sensor values in an XML file. This YAML code will enable Home Assistant to scrape the Weathergoose XML and create sensors.

Step 1: Add this line to configuration.yaml
rest: !include rest.yaml

Step 2: Create rest.yaml and update the resource to the Weathergoose IP address.

Step 3. Restart Home Assistant

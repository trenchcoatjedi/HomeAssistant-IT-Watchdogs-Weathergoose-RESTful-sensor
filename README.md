# IT-Watchdogs Weathergoose RESTful Sensor for Home Assistant 
Create sensors in Home Assistant from data derived from the IT Watchdogs Weathergoose (WxGoos) sensors

The IT Watchdogs Weathergoose (WxGoos) helpfully outputs all it's sensor values in an XML file. This YAML code will enable Home Assistant to scrape the Weathergoose XML and create sensors.

Step 1: Add this line to configuration.yaml

rest: !include rest.yaml

Step 2: Create rest.yaml file 

Step 3: Copy contents of rest.yaml to Home Assistant

Step 4: Update the resource to the Weathergoose IP address. Optionally change the scan_interval number.

Step 5: Restart Home Assistant (full restart; Quick Reload will not work)

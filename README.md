# IT Watchdogs Weathergoose RESTful Sensor for Home Assistant 
Create sensors in Home Assistant from data derived from the IT Watchdogs Weathergoose (WxGoos) sensors using the RESTful API

The IT Watchdogs Weathergoose (WxGoos) helpfully outputs all it's sensor values in an XML file. This YAML code will enable Home Assistant to scrape the Weathergoose XML and create sensors.

Step 1: Add the following line to configuration.yaml

>rest: !include rest.yaml

Step 2: Create rest.yaml file from provided template

Step 3: Update the resource to the Weathergoose IP address. Optionally change the scan_interval number.

Step 4: Restart Home Assistant (full restart; Quick Reload will not work)

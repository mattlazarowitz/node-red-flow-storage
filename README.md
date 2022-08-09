# node-red-flow-storage
This is a personal repo for me to store my various Node Red flows. I often write custom function nodes and I want to have a place to store the custom nodes along with the flows they are part of. I'm still learning Node-Red and Javascript and I think the code quality here reflect that.

The flow "Station AQI vs sensors.json" was a complex flow that polled a couple publicly available sources of AQI data to compare against homebrew sensors (which were also compared against each other) in an effort to see if I could acheve reasonable results with some cheap particulate sensors.
I determined that the PMS5003a was a reasonable perfor,maer, which is probably why Purple Air uses them.

The flow "hwinfo64 remote sensor monitor flow.json" was a flow that worked in conjunction with HWiNFO64 and the addon named Remote Sensor Monitor. Node-Red was used to read the JSON data produced by the addon over the network then use it to log data. This was used to ID a machine that was malfunctioning due to thermal throttling.

The flow "particulate sensor logging.json" is to log data from my homebrew particulate sensors so I could try to make an informed decision about which model of sensor I would use to build more remote sensors.

The flow "storage.json" is to store the work I did to create a UI element that matches the color coded AQI values provided by the EPA.

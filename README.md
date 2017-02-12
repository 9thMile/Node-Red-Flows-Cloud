# Node-Red-Flows-Cloud
This is a set of flows for EOS Weather Station using CloudMQTT Broker

These flows can be used with Node-Red (http://nodered.org/) and will subscribe to a broker account on http://CloudMQTT.com. 
This site has a free account (Cute Cat) which allows 10 concurrenct connections. 
Weather data from a EOS station would be published to this account, see station documentation.

The station name would be subcribed to in the MQTT node --> My Station/#. You can have several stations publishing to the same account.
Node-red is installed on stations at http://{station address}:1880 and dashboard defaults to http://{Station Address}:1880/ui
Default username/password    admin/eosweather
Older stations may need to have Node-Red installed or you can install Node-Red on any MAC/PC/Linux system.

You can adjust the flows for modules that are not included.
Forcast is optional and would need to have rss feeds available for your area. Examples are for NS Canada.

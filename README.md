**OLA trigger config to be used with Broadlink RM 3 Mini to send infra-red commands using DMX (Art-Net, sACN or via DMX input.**  
**Control Eurolite LED Puck Light multicolor IP68 and similar models.**

**Requirements**

* [OLA](https://www.openlighting.org/ola)
* [Node-RED](https://nodered.org)
* [node-red-contrib-simple-broadlink](https://flows.nodered.org/node/node-red-contrib-simple-broadlink)
* [curl](https://curl.haxx.se)
* [Broadlink RM 3 Mini](https://www.ibroadlink.com)


**Installation**
  
* Download the [rm3.conf](rm3.conf) and edit the configuration section
* Download the [rm3_flow.json](rm3_flow.json) file, import it into Node-RED and edit RM 3 Mini hostname settings

[OLA trigger documentation](https://www.openlighting.org/ola/advanced-topics/ola-dmx-trigger/)

**Usage** 

* Before running ola_trigger, make sure that olad is running and the universe has been configured with a DMX512 source.  
The config file is provided on the command line:

`ola_trigger rm3.conf`

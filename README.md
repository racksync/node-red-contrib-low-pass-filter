# Node-RED Low Pass Filter Node

[![Platform](https://img.shields.io/badge/platform-Node--RED-red)](https://nodered.org)
[![node-red-contrib-low-pass-filter](https://img.shields.io/github/v/release/racksync/node-red-contrib-low-pass-filter)](https://github.com/racksync/node-red-contrib-low-pass-filter/releases) [![last commit](https://img.shields.io/github/last-commit/racksync/node-red-contrib-low-pass-filter)](https://github.com/racksync/node-red-contrib-low-pass-filter/commit/)

The Node-RED Node in this repository provides a robust low-pass filter, crucial for signal processing and data smoothing tasks. Designed with a dual-layer filtering approach, it is especially effective for scenarios where data consistency and stability are paramount.

Firstly, the flow utilizes an alpha-based mixing system. Through the adjustable ```Alpha``` parameter, users can define the weight between the new input and the previously processed value, enabling a dynamic level of filtering depending on specific needs.

Secondly, to ensure data integrity, a rate limiter is integrated. By setting the ```Difference``` parameter, users can define the maximum allowable difference between consecutive processed data points. This ensures the filtered output doesn't exhibit rapid or unrealistic jumps, making the flow particularly useful for scenarios like sensor data processing where sudden spikes might be prevalent but are not representative of actual changes.


# Installation

You can install the nodes using "Manage palette" by searching ```low pass filter``` from node-red kebab menu or run the following command in the root directory of your Node-RED installation

```
npm install node-red-contrib-low-pass-filter --save
```

# Usage

Put "Low Pass Filter" into your flow workspace as you wish

![racksync-screenshot](https://github.com/racksync/node-red-contrib-low-pass-filter/blob/main/images/screenshot.png?raw=true)

### Node-RED Node by RACKSYNC
- [Toggle Flows](https://flows.nodered.org/node/@racksync/node-red-contrib-low-pass-filter)
- [Tradfri Remote](https://flows.nodered.org/node/@racksync/node-red-contrib-hass-tradfri-remote)
- [Low Pass Filter](https://flows.nodered.org/node/@racksync/node-red-contrib-low-pass-filter)

![racksync-node](https://github.com/racksync/node-red-contrib-low-pass-filter/blob/main/images/nodes.png?raw=true)

### Tips

- It is recommended to always do a full deploy when you changed some of the nodes of this library to prevent unexpected behavior.
- Always use debug node to test message payload before using in Production.

### Automation Training

- [Product & Services](http://racksync.com)
- [Training & Course](https://facebook.com/racksync)

## [RACKSYNC CO., LTD.](https://racksync.com)

We helps our customers to create life easier across the border of entire technology stack with household and business solutions. We modernize life with Information Technology, Optimize and collect data to make everything possible, secure & trusty
\
\
RACKSYNC COMPANY LIMITED \
Suratthani, Thailand \
Email : devops@racksync.com \
Tel : +66 85 880 8885 

[![Home Automation Thailand Discord](https://img.shields.io/discord/986181205504438345?style=for-the-badge)](https://discord.gg/Wc5CwnWkp4) [![Github](https://img.shields.io/github/followers/racksync?style=for-the-badge)](https://github.com/racksync) 
[![WebsiteStatus](https://img.shields.io/website?down_color=grey&down_message=Offline&style=for-the-badge&up_color=green&up_message=Online&url=https%3A%2F%2Fracksync.com)](https://racksync.com)

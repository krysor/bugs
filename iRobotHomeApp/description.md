# We're having trouble connecting to your robot via Bluetooth

Recently I've tried to connect an iRobot Roomba i7 with the iRobot® HOME App. Every attempt I was getting stuck on this screen:

![error message](./img/connecting.png)

only to get to see this error message after about 2-3 minutes:

![error message](./img/error.png)

This error kept happening despite:

- following the official [iRobot guide]
- having [Optimal firewall configurations]
- not having any [router compability issues]
- trying everything from the official [Connection Issues Troubleshooting Guide]
- tring to switch off the router and use another phone as hotspot
- and following the on screen instructions from the app to a T

## Solution
Try using a different smartphone. In my case it worked instantly on iPhone 14.

I've tried multiple times each:
- fully updated Google Pixel 6a on stock ROM (Android 14)
- fully updated Google Pixel 6a on GrapheneOS
- not fully updated Google Pixel 6 on stock ROM (Android 13)

I've seen at least one another person on Reddit having the exact same problem, having solved it by using a different phone. Also someone from an iRobot Facebook group struggling with a Samsung phone, eventually successfully connecting it using another (Xiaomi) device. Unfortunately I can't find the links anymore.

My theory is that the Samsung foundry SoC's BT modules possibly have some problems when connecting to the iRobot devices.

It's worth to mention that my first ever pairing using a Google Pixel 6a on GrapeheneOS (Android 13) was successfull.

[iRobot guide]: <https://homesupport.irobot.com/s/article/17734>
[Optimal firewall configurations]: <https://homesupport.irobot.com/s/article/9025>
[router compability issues]: <https://homesupport.irobot.com/s/article/10657>
[Connection Issues Troubleshooting Guide]: <https://homesupport.irobot.com/s/article/17735>


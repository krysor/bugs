# We're having trouble connecting to your robot via Bluetooth

Recently I've attempted to connect an iRobot Roomba i7 with the iRobot® HOME App. Every attempt I was getting stuck on this screen:

![error message](./img/connecting.png)

only to see the error message after less than 5 minutes:

![error message](./img/error.png)

This error kept showing up despite:

- following the official [iRobot guide]
- having [Optimal firewall configurations]
- not having any [router compability issues]
- trying everything from the official [Connection Issues Troubleshooting Guide]
- and following the on screen instructions from the app to a T

## Solution
Try using a different smartphone. In my case it worked instantly on iPhone 14.

I've tried:
- fully updated Google Pixel 6a on stock ROM (Android 14)
- fully updated Google Pixel 6a on GrapheneOS
- not fully updated Google Pixel 6 on stock ROM (Android 13)

I've seen at least one another person on Reddit having the exact same problem, having solved it by using a different phone. Also someone struggling with a Samsung phone in a Facebook iRobot group successfully connecting it using a Xiaomi device. Unfortunately I can't find the links anymore.

My theory is that the Samsung foundry SoC's BT modules possibly have some problems when connecting to the iRobot devices.

[iRobot guide]: <https://homesupport.irobot.com/s/article/17734>
[Optimal firewall configurations]: <https://homesupport.irobot.com/s/article/9025>
[router compability issues]: <https://homesupport.irobot.com/s/article/10657>
[Connection Issues Troubleshooting Guide]: <https://homesupport.irobot.com/s/article/17735>


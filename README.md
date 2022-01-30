Updated version of PlatformIO package 'framework-gd32vf103-sdk' using GD32VF103_Firmware_Library_V1.1.3 as the base package.

Branch 'rt-thread' has a small change to 'start.S' so that it can be used with RT-Thread Nano
(https://github.com/RT-Thread/rtthread-nano)

Usage:

```
[env:gd32vf103c_start]
platform = gd32v
platform_packages =
    framework-gd32vf103-sdk @ https://github.com/djix123/framework-gd32vf103-sdk.git
```

or

```
[env:gd32vf103c_start]
platform = gd32v
platform_packages =
    framework-gd32vf103-sdk @ https://github.com/djix123/framework-gd32vf103-sdk.git#rt-thread
```

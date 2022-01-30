Updated version of PlatformIO package 'framework-gd32vf103-sdk' using GD32VF103_Firmware_Library_V1.1.3 as the base package.

Branch 'rt-thread' has small changet to 'start.S' so that it can be uses with RT-Thread Nano
(https://github.com/RT-Thread/rtthread-nano)

Usage:

<code>
[env:gd32vf103c_start]
platform = gd32v
platform_packages =
    framework-gd32vf103-sdk @ https://github.com/djix123/framework-gd32vf103-sdk.git
</code>

or

[env:gd32vf103c_start]
platform = gd32v
platform_packages =
    framework-gd32vf103-sdk @ https://github.com/djix123/framework-gd32vf103-sdk.git#rt-thread


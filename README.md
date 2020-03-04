# Introduction [中文][chinese]

<p align="center">
  <img src="https://github.com/VRTRIX/VRTRIXGlove_Unity3D_SDK/blob/master/docs/img/digital_glove.png"/>
</p>


VRTRIX Data Glove is a product based on high accuracy IMU modules that populated on each finger & hand. Each IMU result can detect rotation of one joint. Combined with sophisticated Inverse-Kenetic Algorithm,  VRTRIX Data Glove is able to detect & simulate all gestures of human hands with six IMUs per hand (12 for a pair). 

VRTRIX IMU modules includes 9-axis sensors (gyro, accel & mag), where rotation quaternions are calculated with adaptive multi-state Kalman Filter algorithms and the output of the data stream is up to 400Hz while the latency of this module remain under 5ms. All IMU modules are connected to RF processor and the sensor tracking data packets are transmitted through 2.4GHz proprietary protocol. Thanks to the strict power control during the system design, the glove's battery can last at least 30 hours even when heavily used. The time latency between rotating your hands and the virtual hand gesture rendered in VR headset is less than 10ms. Lightning fast real-time response, precise tracking and full finger gesture detection brings the most impressive interactive experience to Virtual Reality!

# VRTRIXGlove_Installer

This repository contains the VRTRIX Glove Client Installer, which is useful for hardware driver installation, hardware port auto configuration, data gloves pairing to dongle and demo testing. 

Please note that this client installer (or standalone driver installer) is **mandatory** before use any other SDKs (including Unity3D, UE4, MotionBuilder and C++). Please Check the installation and operation method [here][here]

Following are the links to SDKs for different platforms:

[Unity3D][Unity3D]: support from Unity 2017.1.1

[Unreal Engine 4][Unreal Engine 4]: support from 4.18

[MotionBuilder][MotionBuilder]: support from MotionBuilder 2016

[C++][C++]: support from Visual Studio 2017

**To download VRTRIX Glove latest stable Client Installer Release, visit [our release page][devsite].**

**For detailed information about using our installer, check out the docs included in [release page][devsite]!**

## Support

- VRTRIXGlove_Installer supports Windows 10 OS**
- If you need any techincal support, please contact info@vrtrix.com

[chinese]: https://github.com/VRTRIX/VRTRIXGlove_Installer/blob/master/README_CN.md "chinese"
[devsite]: https://github.com/VRTRIX/VRTRIXGlove_Installer/releases "VRTRIX Glove Installer Release site"
[here]: https://github.com/VRTRIX/VRTRIXGlove_Installer/blob/master/docs/%E5%8C%97%E4%BA%AC%E6%97%A0%E8%BF%9C%E5%BC%97%E5%B1%8A%E6%95%B0%E6%8D%AE%E6%89%8B%E5%A5%97(VRTRIX%20Data%20Glove)%E6%93%8D%E4%BD%9C%E6%89%8B%E5%86%8C.pdf
[Unity3D]: https://github.com/VRTRIX/VRTRIXGlove_Unity3D_SDK
[Unreal Engine 4]: https://github.com/VRTRIX/VRTRIXGlove_UE4_SDK
[MotionBuilder]: https://github.com/VRTRIX/VRTRIXGlove_MotionBuilder_Plugin
[C++]: https://github.com/VRTRIX/VRTRIXGloveCppSDK

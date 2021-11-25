# 功能介绍 [English][english]

<p align="center">
  <img src="https://github.com/VRTRIX/VRTRIXGlove_Unity3D_SDK/blob/client/docs/img/digital_glove.png"/>
</p>

VRTRIX 数据手套基于高精度惯性传感器，定位手指各关节和手腕动作与姿态。每只手套上分布有6个传感器，双手共12个，可以实时高精度低延迟输出全手所有关节的运动姿态。
VRTRIX 惯性传感器模块采用九轴传感器（3轴陀螺仪，3轴加速度计，3轴磁力计），精确高效的数据融合算法保证传感器以每秒400Hz的频率输出精确的姿态四元数，同时保证数据延迟低于5ms。VRTRIX数据手套还搭载无线传输功能，双手传感器数据可以通过手背上的无线发射模块实时发送给pc并进行渲染。无线传输采用2.4GHz专有协议，安全高效延迟不超过10ms。同时，系统进行了低功耗设计，数据手套不间断使用情况下的电池续航时间可以达到30小时以上。

# VRTRIXGlove_Installer

 该软件为VRTRIX数据手套客户端配置软件，集成了硬件驱动，端口自动配置，配对还有demo测试的功能。
 
 请注意：该软件(或者独立驱动安装包)在运行任何平台SDK之前**必须**首先安装，以保证硬件驱动正确。具体的操作手册可在[这里][here]查看。
 
 以下为VRTRIX数据手套目前支持的平台SDK链接：
 
[Unity3D][Unity3D]: 支持 Unity 2017.1.1及以上版本

[Unreal Engine 4][Unreal Engine 4]: 支持 4.18 及以上版本

[MotionBuilder][MotionBuilder]: 支持 MotionBuilder 2016 及以上版本

[C++][C++]: 支持 Visual Studio 2017 及以上版本

**请前往我们github的[release页面][devsite]下载最新的稳定版本客户端配置软件。**

**如果想获得更多详细的关于该客户端配置软件的使用方法和信息，请前往我们github的[release页面][devsite]下载。**

## 支持

- VRTRIXGlove_Installer 支持 Windows 10 OS**
- 如果你需要任何额外的技术帮助，请联系info@vrtrix.com。

[devsite]: https://github.com/VRTRIX/VRTRIXGlove_Installer/releases "VRTRIX Glove Installer Release site"
[here]: https://github.com/VRTRIX/VRTRIXGlove_Installer/blob/master/docs/%E5%8C%97%E4%BA%AC%E6%97%A0%E8%BF%9C%E5%BC%97%E5%B1%8A%E6%95%B0%E6%8D%AE%E6%89%8B%E5%A5%97(VRTRIX%20Data%20Glove)%E6%93%8D%E4%BD%9C%E6%89%8B%E5%86%8C.pdf
[Unity3D]: https://github.com/VRTRIX/VRTRIXGlove_Unity3D_SDK
[Unreal Engine 4]: https://github.com/VRTRIX/VRTRIXGlove_UE4_SDK
[MotionBuilder]: https://github.com/VRTRIX/VRTRIXGlove_MotionBuilder_Plugin
[C++]: https://github.com/VRTRIX/VRTRIXGloveCppSDK
[english]: https://github.com/VRTRIX/VRTRIXGlove_Unity3D_SDK/blob/master/README.md "english"

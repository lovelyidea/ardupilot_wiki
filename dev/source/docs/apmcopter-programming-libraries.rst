.. _apmcopter-programming-libraries:

===============================
ArduPilot程序库
===============================

\ `库文件 <https://github.com/ArduPilot/ardupilot/tree/master/libraries>`__ 由Copter、Plane和Rover共享。下面是一些顶层库以及对应的功能列表。

**核心库：**

-  `AP_AHRS <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_AHRS>`__ -
   使用DCM或者EKF估计姿态
-  `AP_Common <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_InertialNav>`__ -
   所有程序和库所需的核心
-  `AP_Math <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_Math>`__ -
   多种数学函数，特别是向量操作
-  `AC_PID <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AC_PID>`__ -
   PID控制器
-  `AP_InertialNav <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_InertialNav>`__ -
   惯性导航库，用于惯导信息和GPS信息以及气压信息的融合
-  `AC_AttitudeControl <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AC_AttitudeControl>`__
   -姿态控制
-  `AP_WPNav <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_InertialNav>`__
   -路径点导航
-  `AP_Motors <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_Motors>`__
   - 多旋翼和常规布局直升机的电机混控
-  `RC_Channel <https://github.com/ArduPilot/ardupilot/tree/master/libraries/RC_Channel>`__ -
   将PWM输入/输出从APM_RC转换为内部单位，例如：角度
-  `AP_HAL <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_HAL>`__,
   `AP_HAL_AVR <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_HAL_AVR>`__,
   `AP_HAL_PX4 <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_HAL_PX4>`__
   - 实现“硬件抽象层”，该层对高层代码提供统一的接口，以使高层代码便于移植到不同的硬件

**传感器库：**

-  `AP_InertialSensor <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_InertialSensor>`__ -
   读取陀螺仪和加速度计数据，执行校准，并以标准单位想主程序或者其它库提供数据
-  `AP_RangeFinder <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_RangeFinder>`__ -
   声纳和红外接口
-  `AP_Baro <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_Baro>`__ -
   气压计接口
-  `AP_GPS <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_GPS>`__ -
   GPS接口
-  `AP_Compass <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_Compass>`__ -
   3轴磁罗盘接口
-  `AP_OpticalFlow <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_OpticalFlow>`__ -
   光流接口

**其它库：**

-  `AP_Mount <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_Mount>`__, \ `AP_Camera <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_Camera>`__, \ `AP_Relay <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_Relay>`__ -
   云台控制以及相机快门控制
-  `AP_Mission <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_Mission>`__
   - 在eeprom中存储/恢复任务指令
-  `AP_Buffer <https://github.com/ArduPilot/ardupilot/tree/master/libraries/AP_Buffer>`__ -
   惯导所使用的简单FIFO缓冲器
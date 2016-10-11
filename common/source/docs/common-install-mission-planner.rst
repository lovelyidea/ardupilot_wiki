.. _common-install-mission-planner:

==========================
安装 Mission Planner 地面站
==========================

*Mission Planner* 是免费使用的, 适用于Windows的开源软件.
这些说明将指导您将 *Mission Planner*
地面站成功安装在您的电脑上.

下载最新的Mission Planner安装程序文件
=======================================================

从这里下载最新的 `Mission Planner安装程序 <http://firmware.ardupilot.org/Tools/MissionPlanner/MissionPlanner-latest.msi>`__.

运行安装程序
============================

打开Microsoft安装程序文件（.msi）并选择运行安装程序.

.. image:: ../../../images/installation.png
    :target: ../_images/installation.png

按照说明完成设置过程。 安装实用程序将自动安装任何必要的软件驱动程序 如果您收到DirectX安装错误，请从DirectX下载中心更新您的DirectX插件 `DirectX下载中心 <http://www.microsoft.com/en-us/download/details.aspx?id=35>`__.

I如果收到此处所示的警告，请选择 **仍然安装此驱动程序软件** 以继续.

.. image:: ../../../images/driver_installation_warning.png
    :target: ../_images/driver_installation_warning.png

*Mission Planner* 通常安装在 **C:\\Program Files
(x86)\\APM Planner** 文件夹或 \ **C:\\Program Files\\APM Planner**
文件夹中. 这就是你的日志文件的文件夹的位置.

在安装过程中，将根据您的选择创建用于打开 *Mission Planner*的图标

打开 Mission Planner
====================

安装完成后, 通过点击图标打开 *Mission Planner* 

然后你可以:

-  :ref:`将 Mission Planner 和飞控连接 <common-connect-mission-planner-autopilot>` 可以通过数传遥测和控制飞行器, 或者
-  :ref:`刷写固件 <common-loading-firmware-onto-pixhawk>`

更新 Mission Planner
========================

*Mission Planner* 会自动通知您有可用的更新
(在连接到互联网时).

请始终运行最新版本的Mission Planner.

[copywiki destination="copter,plane,rover,planner"]

[site wiki="planner"]

.. toctree::
    :maxdepth: 1

    Mission Planner Advanced Installation <mission-planner-advanced-installation>
[/site]

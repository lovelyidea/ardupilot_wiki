.. _common-loading-firmware-onto-pixhawk:

========================================
在Pixhawk / APM2.x / PX4上刷写固件
========================================

这些说明将告诉您如何下载最新的固件刷写到Pixhawk，APM2.x或PX4控制器.

[copywiki destination="copter,plane,rover,planner"]

将控制器连接到电脑
==============================

将 :ref:`Mission Planner安装到计算机 <common-install-mission-planner>` 上后, 使用micro USB数据线将飞控连接到计算机，如下所示。 在计算机上直接使用USB端口（不要用USB集线器）.

.. figure:: ../../../images/pixhawk_usb_connection.jpg
   :target: ../_images/pixhawk_usb_connection.jpg

   Pixhawk USB连接

.. figure:: ../../../images/apm_micro_usb.jpg
   :target: ../_images/apm_micro_usb.jpg

  APM USB连接

.. figure:: ../../../images/PX4FMU_PX4IO_USB.jpg
   :target: ../_images/PX4FMU_PX4IO_USB.jpg

   PX4 USB连接

Windows应该会自动检测到飞控并安装正确的驱动程序
软件


连接到Mission Planner
==========================

打开 *Mission Planner* 并选择屏幕右上角的COM端口下拉菜单 (靠近 **连接** 按钮).  选择
**AUTO** 或板卡的特定端口 (**PX4 FMU** 和 **Arduino
Mega 2560**). 将波特率设置为 **115200** 如图所示. 先不要点击
**连接** .

.. image:: ../../../images/Pixhawk_ConnectWithMP.png
    :target: ../_images/Pixhawk_ConnectWithMP.png

.. image:: ../../../images/connect-to-com-port.png
    :target: ../_images/connect-to-com-port.png

安装固件
================

在Mission Planner's**初始设置\ | 安装固件**屏幕
选择与您的机架相匹配的适当图标（即四轴，六轴）。
当它问你"Are you sure?"回答**YES**

.. figure:: ../../../images/Pixhawk_InstallFirmware.jpg
   :target: ../_images/Pixhawk_InstallFirmware.jpg

   Mission Planner: 安装固件图示

After the Mission Planner detects which board you are using (i.e.
Pixhawk) it will ask you to unplug the board, plug it back in and then
press **OK** within a few seconds (during this brief period the
bootloader accepts requests to upload new firmware).

.. figure:: ../../../images/Pixhawk_InstallFirmware2.png
   :target: ../_images/Pixhawk_InstallFirmware2.png

   Mission Planner: Install FirmwarePrompt

If all goes well you will see some status appear on the bottom right
including the words, "erase...", "program...", "verify.." and "Upload
Done".  The firmware has been succesfully uploaded to the board.

Testing
=======

You can test the firmware is basically working by switching to the
*Mission Planner Flight Data* screen and pressing the **Connect**
button.  The HUD should update as you tilt the board.

:ref:`Connect Mission Planner to AutoPilot <common-connect-mission-planner-autopilot>` has more
information on connecting to Mission Planner.

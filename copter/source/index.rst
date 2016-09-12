.. _home:

===========
Copter Home
===========

.. tip::

 ArduPilot 开发者生态系统正在创新发展!  `点击这里查看详细内容 … <http://diydrones.com/profiles/blogs/a-new-chapter-in-ardupilot-development>`__


.. image:: /images/home_copter.jpg
    :target: _images/home_copter.jpg

..  raw:: html

    <table>
    <tr>
    <td width="48%">

|TOP_COL_LEFT|


..  raw:: html

    </td>
    <td width="4%">
    </td>
    <td width="48%">
    

|TOP_COL_RIGHT|    

..  raw:: html

    </td>
    </tr>
    </table>
    
..  raw:: html

    <table>
    <tr>
    <td width="48%">

.. image:: ../../images/mission_planner_spline_waypoint.jpg
    :target: _images/mission_planner_spline_waypoint.jpg
    :width: 350px
           
..  raw:: html

    </td>
    <td width="4%">
    </td>
    <td width="48%">

.. image:: ../../images/mission_planner_flight_data.jpg
   :target: _images/mission_planner_flight_data.jpg    
   :width: 350px

..  raw:: html

    </td>
    </tr>
    </table>


--------------

系统组成
~~~~~~~~~~~~~~~~~


- 搭载最新 `多旋翼固件 <http://firmware.ardupilot.orgd/>`__. 的`Pixhawk <https://store.3dr.com/t/pixhawk>`__ 或者 :ref:`其他自驾仪 <common-autopilots>` 
-  :ref:`Mission Planner软件 <planner:home>` --让用户更方便的通过地面站调整安装、功能配置。
-  此多旋翼Wiki有着你安装、调试多旋翼或传统直升机的所有知识。 
-  一个适合你作业任务的
   :ref:`多旋翼飞机 <build-your-own-multicopter>` 或者
   :ref:`直升机 <traditional-helicopters>` for your mission.
-  此外还有很多其他有用的功能附件，比如数传电台，可以用它实现电脑和飞行器的控制与数据传输功能。

--------------

旋翼飞行器类型
~~~~~~~~~~~~~~~~~

..  raw:: html

    <table>
    <tr>
    <td width="48%">

.. image:: /images/helicopter_trex450.jpg
   :target: _images/helicopter_trex450.jpg 
   :width: 211px

..  raw:: html

    </td>
    <td width="4%">
    </td>
    <td width="48%">

.. image:: /images/3DR_arducopter_hexa_b_frame.jpg
   :target: _images/3DR_arducopter_hexa_b_frame.jpg
   :width: 211px

..  raw:: html

    </td>
    </tr>
    </table>


:ref:`Multicopters <what-is-a-multicopter-and-how-does-it-work>`:

-  Utilize differential thrust management of independent motor-prop
   units to provide lift and directional control
-  Benefit from mechanical simplicity and design flexibility
-  A capable payload lifter that's functional in strong wind conditions
-  Redundant lift sources can give increased margin of safety
-  Varied form factor allows convenient options for payload mounting.


:ref:`Helicopters <traditional-helicopters>`:

-  Typically use a single lifting rotor with two or more blades
-  Maintain directional control by varying blade pitch via
   servo-actuated mechanical linkage (many versions of these craft exist
   and it is beyond the scope of this manual to cover them all -- the
   mechanical systems used in helicopters warrant special study and
   consideration)
-  Strong, fast and efficient -- a proven-worker suitable to many missions.



Because of its open design, Copter also supports more unusual frame
types including the :ref:`Single and Coax-Copters <singlecopter-and-coaxcopter>`.  Put this together
with :ref:`Plane <plane:home>`,
:ref:`Rover <rover:home>` and :ref:`Antenna Tracker <antennatracker:home>` and you have a system
of robotic vehicles that can be controlled through very similar
interfaces to accomplish a wide variety of tasks.

.. image:: ../../images/firmware_types.jpg
    :target: _images/firmware_types.jpg


--------------

更多内容
~~~~~~~~~~~~~~~~~

-  Continue to the :ref:`Introduction section of this wiki. <introduction>`
-  Visit `DIYDrones.com <http://diydrones.com/>`__ a large community of
   UAV enthusiast largely clustered around the ArduPilot family of autopilots.
-  Use the `APM Forums <http://ardupilot.com/forum/viewforum.php?f=3>`__
   to ask support questions and advice.
-  Read or join the `drones-discuss email list <https://groups.google.com/forum/#!forum/drones-discuss>`__ once
   you're ready to get involved with the development of the software platform.



.. toctree::
   :hidden:
   
   多旋翼简介 <docs/introduction>
   First Time Setup <docs/initial-setup>
   First Flight <docs/flying-arducopter>
   Advanced Configuration <docs/common-advanced-configuration>
   Mission Planning <docs/common-mission-planning>
   Mission Analysis <docs/common-mission-analysis>
   Optional Hardware <docs/common-optional-hardware>
   Traditional Helicopters <docs/traditional-helicopters>
   Tricopter <docs/tricopter>
   SingleCopter and CoaxCopter <docs/singlecopter-and-coaxcopter>
   AutoPilot Hardware Options <docs/common-autopilots>
   Use-Cases and Applications <docs/common-use-cases-and-applications>
   Antenna Tracking <docs/common-antenna-tracking>
   Simulation <docs/common-simulation>
   Appendix <docs/common-appendix>
   Full Table of Contents <docs/common-table-of-contents>



.. |TOP_COL_LEFT| replace:: This is the full-featured, :ref:`open-source <dev:license-gplv3>` 
   multicopter UAV controller that won the   
   `Sparkfun 2013 and 2014 Autonomous Vehicle Competition <https://avc.sparkfun.com/>`__ 
   (dominating with the top five spots). A team of developers 
   from around the globe are constantly improving and refining 
   the performance and capabilities of Copter.
   
.. |TOP_COL_RIGHT| replace:: Copter is capable of the full range of flight requirements 
   from fast paced FPV racing to smooth aerial photography to fully autonomous 
   complex missions which can be programmed through one of 4 elegant and well-developed 
   software ground stations. The entire package is designed to be safe, feature rich, 
   open-ended for custom applications and increasingly easy to use even for novice users.



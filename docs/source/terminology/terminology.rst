A-Z Terminology Explained
=========================

Driver Station
--------------

Driver Station is the tool that connects to the roboRIO on the robot. Through Driver Station, you are able to enable (run your code that's deployed on the robot) and disable (stops running the deployed code) the robot.
Driver Station also has a built in error logger, which can help to detect errors during runtime. Driver Station also shows inputs from external devices like controllers.

Shuffleboard / SmartDashboard
-----------------------------

SmartDashboard is a tool that allows users to display whatever value they want by using a ``key, value`` system. SmartDashboard stores values in NetworkTables.
Shuffleboard is a nicer display of SmartDashboard, and allows choosing of options as well as display of options.

NetworkTables
-------------

A dictionary system implemented by WPILib. Values are stored and referenced by a key, which is a string. 

REV Hardware Client
-------------------

A hardware client provided by REV Robotics for REV products, such as SparkMaxes, etc. 

REV SparkMax Client
-------------------

A client to update the firmware of the SparkMax motor controllers as well as graphing PID.

roboRIO
-------

The "brain" of the robot. The roboRIO handles all code and periodic looping.

roboRIO Imaging Tool
--------------------

A tool used to update the firmware of the roboRIO. Can also be used to set the team number of the roboRIO.
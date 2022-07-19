Troubleshooting RoboRIO Imaging
===================================

The RoboRIO 1 and 2 most commonly face problems with imaging.

.. note::

   This page will be updated as we are alerted of more problems and fixes.


Imaging for the First Time (RoboRIO 2 Only)
-------------------------------------------
If imaging the RoboRIO 2 for the first time, you must do it via microSD card. Follow the guide `here on WPILib's documentation. <https://docs.wpilib.org/en/stable/docs/software/roborio-info/roborio2-imaging.html>`_
After imaging the SD card, make sure to connect to the RoboRIO and apply the team number by entering your team number on the RoboRIO Imaging Tool and clicking :guilabel:`Apply`.

Generic Troubleshooting
------------------------

# **1. Open the Imaging Tool via Desktop Icon**
When opening the RoboRIO Imaging Tool, click the shortcut created on your desktop rather than searching for it.
The shortcut runs the program as administrator, which might fix issues.


# **2. Check your laptop name**
The RoboRIO has an issue with imaging from laptops with non-alphanumeric characters in their names (dashes). Change your laptop name to something with only alphanumeric characters and try again.
For instance, :guilabel:`LAPTOP-123` will **not** work, while :guilabel:`LAPTOP123` works just fine.


# **3. Firewall and Virus Protection** 
Turn off your firewall and virus protection, they often impede formatting of the RoboRIO. Try again after doing so.

# **4. Turn off the console output**
If the above fixes do not work, try clicking :guilabel:`Edit Startup Settings` in the RoboRIO Imaging Tool and unchecking :guilabel:`Enable console output`. 
Apply the change and restart the RoboRIO. 
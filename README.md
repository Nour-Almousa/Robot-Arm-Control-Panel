# Robot Arm Control Panel

A web page with 6 sliders to control a robot arm in addition to 5 buttons controlling the movement of the robot arm base.

![Screenshot ](https://user-images.githubusercontent.com/86366710/123860945-3de46280-d92f-11eb-9dfb-dd678cd2ce8f.png)

## Files in repository

* **RobotArm.php**: this file includes the HTML code for the structure of the page, a small Javascript code for displaying the values of each slider, and PHP code to update the  values in the database.
* **connect.php**: PHP code for establishing the connection with the database.
* **mystyle.css**: includes the code for styling the web page.
*  **robot_arm_db.sql**.

## Database 
There is one table in the database (robot_arm_db) with 8 columns: 
- 6 for the values of each slider
- 1 for the value of "on" button
- 1 stores a character representing which button is pressed (s for stop, r for right , and so on)

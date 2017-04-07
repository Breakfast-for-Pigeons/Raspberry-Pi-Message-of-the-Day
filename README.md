# Raspberry Pi Message of the Day
Instructions for making a cool login script for the Raspberry Pi.

Check out my Wiki page for more detailed instructions: https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/wiki

1. Open a terminal and type **sudo nano /etc/motd**

![](https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/blob/master/images/motd_1.png)

2. Delete everything that is currenty in the message. Save and exit.

3. In a terminal window, type **sudo nano /usr/local/bin/(script)**. For example, if you are using the raspberry_pi_3_motd.sh script, type **sudo nano /usr/local/bin/raspberry_pi_3_motd.sh**.


4. Enter your script.  Save the script and exit. (Use one of the scripts above)

5. Make the script executable. To do this, type **sudo chmod +x /usr/local/bin/(script)**. For example, if you are using the raspberry_pi_3_motd.sh script, type **sudo chmod +x /usr/local/bin/raspberry_pi_3_motd.sh**.

6. Add the script to your profile. In a terminal window, type **sudo /etc/profile** and then after the last line, add /usr/local/bin/(script). For example, if you are using the raspberry_pi_3_motd.sh script, type **/usr/local/bin/raspberry_pi_3_motd.sh**.

7. Go to Menu → Preferences → Raspberry Pi Configuration, and select Boot to CLI (Command Line Interface. Then click OK to save.

Instead of a graphical boot, you will boot to a command line. After logging in, you will see your message of the day. NOTE: To get to the GUI, type **startx** on the command line.









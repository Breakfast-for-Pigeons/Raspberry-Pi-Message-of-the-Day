# Raspberry Pi Message of the Day
Instructions for making a cool login script for the Raspberry Pi.

1. Open a terminal and type **sudo nano /etc/motd**

![](https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/blob/master/images/motd_1.png)

2. Delete everything that is currenty in the message. Save and exit.

![](https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/blob/master/images/motd_2.png)

3. Next, type **sudo nano /usr/local/bin/(script)**. For example, if you are using the raspberry_pi_3_motd.sh script, type **sudo nano /usr/local/bin/raspberry_pi_3_motd.sh**. NOTE: In my example below, I just named the file motd.sh

![](https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/blob/master/images/motd_3.png)

4. Enter your script.  Save the script and exit. (Just copy and paste the contents of one of the scripts above.)

5. Make the script executable. To do this, type **sudo chmod +x /usr/local/bin/(script)**. For example, if you are using the raspberry_pi_3_motd.sh script, type **sudo chmod +x /usr/local/bin/raspberry_pi_3_motd.sh**. NOTE: In my example below, I just named the file motd.sh

![](https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/blob/master/images/motd_5.png)

6. Add the script location to your profile. In a terminal window, type **sudo /etc/profile** and then after the last line, add /usr/local/bin/(script). For example, if you are using the raspberry_pi_3_motd.sh script, type **/usr/local/bin/raspberry_pi_3_motd.sh**. NOTE: In my example below, I just named the file motd.sh. The # indicates a comment and will be ignored by the system. It's there to let other users know that the line below is for the message of the day.

![](https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/blob/master/images/motd_6a.png)

![](https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/blob/master/images/motd_6b.png)

7. Go to Menu → Preferences → Raspberry Pi Configuration, and select Boot to CLI (Command Line Interface. Then click OK to save.

![](https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/blob/master/images/motd_7.png)

Instead of a graphical boot, you will boot to a command line. After logging in, you will see your cool message of the day. NOTE: To get to the GUI, type **startx** on the command line. 

![](https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/blob/master/images/raspberry_pi_motd.png)

![](https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/blob/master/images/Raspberry_Pi_2_motd.png)

![](https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/blob/master/images/raspberry_pi_3_motd.png)

![](https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/blob/master/images/raspberry_pi_zero_motd.png)

![](https://github.com/ShineTop/Raspberry-Pi-Message-of-the-Day/blob/master/images/raspberry_pi_zero_w_motd.png)









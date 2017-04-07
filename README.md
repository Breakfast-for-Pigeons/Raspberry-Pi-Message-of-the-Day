# Raspberry Pi Message of the Day
Instructions for making a cool login message for the Raspberry Pi.

1. Open a terminal and type **sudo nano /etc/motd**

![motd_1](https://cloud.githubusercontent.com/assets/13591438/24821039/ef332688-1bb1-11e7-9ae0-abe83667f514.png)

2. Delete everything that is currenty in the message. Save and exit.

![motd_2](https://cloud.githubusercontent.com/assets/13591438/24821045/f9c03ea6-1bb1-11e7-9901-954fdd13d2b2.png)

3. Next, type **sudo nano /usr/local/bin/(script)**. For example, if you are using the raspberry_pi_3_motd.sh script, type **sudo nano /usr/local/bin/raspberry_pi_3_motd.sh**. NOTE: In my example below, I just named the file motd.sh

![motd_3](https://cloud.githubusercontent.com/assets/13591438/24821048/fd4b4fd4-1bb1-11e7-955d-365c6ef4d832.png)

4. Enter your script.  Save the script and exit. (Just copy and paste the contents of one of the scripts above.)

5. Make the script executable. To do this, type **sudo chmod +x /usr/local/bin/(script)**. For example, if you are using the raspberry_pi_3_motd.sh script, type **sudo chmod +x /usr/local/bin/raspberry_pi_3_motd.sh**. NOTE: In my example below, I just named the file motd.sh

![motd_5](https://cloud.githubusercontent.com/assets/13591438/24821052/01929fe8-1bb2-11e7-9696-e9bd913630c0.png)

6. Add the script location to your profile. In a terminal window, type **sudo /etc/profile** and then after the last line, add /usr/local/bin/(script). For example, if you are using the raspberry_pi_3_motd.sh script, type **/usr/local/bin/raspberry_pi_3_motd.sh**. NOTE: In my example below, I just named the file motd.sh. The # indicates a comment and will be ignored by the system. It's there to let other users know that the line below is for the message of the day.

![motd_6a](https://cloud.githubusercontent.com/assets/13591438/24821055/05e8d472-1bb2-11e7-8aec-d89c4bb4d97c.png)

![motd_6b](https://cloud.githubusercontent.com/assets/13591438/24821058/099e07ea-1bb2-11e7-9dc6-798ee037810e.png)

7. Go to Menu → Preferences → Raspberry Pi Configuration, and select Boot to CLI (Command Line Interface. Then click OK to save.

![motd_7](https://cloud.githubusercontent.com/assets/13591438/24821061/0ca52ab8-1bb2-11e7-81aa-855707c3784c.png)

Instead of a graphical boot, you will boot to a command line. After logging in, you will see your cool message of the day. NOTE: To get to the GUI, type **startx** on the command line. 

![raspberry_pi_motd](https://cloud.githubusercontent.com/assets/13591438/24821070/16b6ef3c-1bb2-11e7-92da-4fc270def90b.png)

![raspberry_pi_2_motd](https://cloud.githubusercontent.com/assets/13591438/24821077/1d98dbda-1bb2-11e7-92d9-aca6a0e3fa92.png)

![raspberry_pi_3_motd](https://cloud.githubusercontent.com/assets/13591438/24821083/2375048e-1bb2-11e7-8cdb-d3cd58b27e02.png)

![raspberry_pi_zero_motd](https://cloud.githubusercontent.com/assets/13591438/24821090/2bb7d004-1bb2-11e7-9945-197edd068dc2.png)

![raspberry_pi_zero_w_motd](https://cloud.githubusercontent.com/assets/13591438/24821094/3269bff2-1bb2-11e7-8e0e-5d548637d4a9.png)









# Raspberry-Pi-Message-of-the-Day
Instructions fo making a cool login script for the Raspberry Pi.

1. Open a terminal and type sudo nano /etc/motd


2. Delete everything that is currenty in the message. Save and exit.

3. In a terminal window, type sudo nano /usr/local/bin/<name of your script>. In my case, I named it motd.sh


4. Enter your script.  Save the script and exit.

5. Make the script executable. To do this, type sudo chmod +x /usr/local/bin/<name of your script>. In my case, I typed sudo chmod +x /usr/local/bin/motd.sh


6. Add the script to your profile. In a terminal window, type sudo /etc/profile and then after the last line, add /usr/local/bin/<name of your script>.

    


7. Go to Menu → Preferences → Raspberry Pi Configuration, and select Boot to CLI (Command Line Interface. Then click OK to save.









Instead of a graphical boot, you will boot to a command line. After logging in, you will see your message of the day.









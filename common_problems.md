## Common issues

Please check these common problem solving steps before raising an issue:-

# Google Assistant says  "I need your permission to help you"

You’ve missed turning on a blue slider at the step where you have to give the google assistant access to you google activities history. 

Open the Activity Controls page https://myaccount.google.com/activitycontrols for the Google account that you want to use with the Assistant. Ensure the following toggle switches are enabled (blue):

    1. Web & App Activity - Make sure the box marked "Include Chrome browsing history and activity from websites and apps that use Google Services" is also checked 
    2. Location History
    3. Device Information
    4. Voice & Audio Activity

# The skill keeps asking me to link my Google Account

This seems to be an issue with the Google Amazon authentication. The fix for this is as follows:-

1. Unlink the deauthorise the app aby removing it from your google account by going here https://myaccount.google.com/permissions?pli=1 and select the app called "alexa-assistant".
2. Click on the button labelled "Remove Access"
3. Press "Yes" to confirm

![alt text](screenshots/app_remove.jpeg)

4. Go to the Alexa web app and log in alexa.amazon.com
5. Select "Skills" from the Home menu on the right hand side of the screen

![alt text](screenshots/home_skills.jpg)

6. Click on "Your Skills" at the top right

![alt text](screenshots/your_skills.jpg)

7. Click on "Dev Skills"

![alt text](screenshots/dev_skills.jpg)

8. Click on the skill called "Google Assistant for Alexa"

![alt text](screenshots/assistant_skill.jpg)

9. Click on "Disable Skill"

![alt text](screenshots/disable_skill.jpg)

10.  Now click on "Enable Skill"

![alt text](screenshots/enable_skill.jpg)

11. Select the Google account you want to use and then make sure you click "Allow" on the Google authorisation page. 

![alt text](screenshots/authorise.jpeg)


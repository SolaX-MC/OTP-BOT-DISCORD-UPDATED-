# OTP-BOT-DISCORD-UPDATED-
Simple OTP Bot, working with any company or service name. New OTP Bot, working with any company or service name to fetch otp code.


Send command: "/dial" to start grabbing your OTP.

THIS SOURCE CODE IS FREE AND FOR EDUCATION PURPOSE ONLY.


SETUP

Download ngrok and run ngrok.exe http 5000
Download python and Install
Unzip Your Bot files

pip3 install discord
pip install Flask
pip install discord-py-slash-command
pip install twilio

# First create a discord group
Go to your discord developer page  https://discord.com/developers/applications/
Click "New Application", create application
Click "OAuth2"
Click "URL Generator"

 # OAuth2 URL Generator Page

 # SCOPE
 Check "Bot"
 Check "applications.commands"

 # BOT PERMISSIONS
 Check All Permissions
 Dont check "Administrator"

 # GENERATED URL
 Copy the URL
 Open new Tab in your browser where you logged your discord
 Paste the URL and follow it, authorize the Bot in your group.
 Go back to to your discord developer Tab
 Left side, click "Bot" and click "add" Bot
 Left side, click "Bot" and click "add" Bot
 Click "Reset Token" and click "Copy" to copy token
 Open "bot.py" add bot_token
 Go to discord server/group 
 Left side, right-click on the server and click "copy ID"
 Go to "bot.py" add server_id

 # Twilio Details
 Go to Twilio Account Copy "Account SID" 
 Go to "bot.py" add account_sid
 Go to Twilio Account again Copy "Auth Token" 
 Go to "bot.py" add auth_token
 Go to Twilio Account again Copy "Your Twilio Phone Number" 
 Go to "bot.py" add Twilio Phone Number (e.g "+1987654321")
 Go to terminal where you run ngron, copy your https link/url
 Go to "bot.py" add ngrok_url
 Save bot.py, close file and run bot.py in python
 Run talker.py in python

 # Start Calling
 Go to your server and type command: "/dial" and fill your info.
 E.G: /dial cell_phone:+1987654321 otp_digits:6 client_name:Smith company_name:PayPal

# telegram-discord-integration
An application which will send messages from Telegram to Discord.

<b>Requirements</b><br>
This application requires Telethon and Discord Webhook. You must also create a Telegram application on their website. 

Python Libraries:<br>
Telethon - https://pypi.org/project/Telethon/<br>
Discord Webhook - https://pypi.org/project/discord-webhook/

Telegram Application Information:<br>
https://core.telegram.org/api/obtaining_api_id

<b>How does it work?</b><br>
This application uses Telethon to fetch the messages being sent on the Telegram channels specified in the configuration file, afterwards sending them to the specified webhook. The Telegram application settings and channels can be configured in the files which will be created after its execution.<br><br>
As of right now this application only supports text messages, soon I will work on media such as images and videos.

<b>How to configure it?</b><br>
Telegram Application Credentials:<br>
Once the script is executed for the first time, it will create 'config.json'. In this file, you must specify the details of the Telegram application you created.

Discord Webhook:<br>
After the previous step, a Discord Webhook must created. The article below contains information regarding the creation of a webhook.<br>
Discord Webhook Creation - https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks<br>

After the webhook has been created, proceed to specify the link in the 'config.json' file.


Channel IDs:<br>
After entering the correct credentials, the script must be executed a second time to create 'channels.json'. This file will contain the names and IDs of the channels separated by a delimeter. The name is irrelevant, but the channel's ID must be valid.

<b>How to get the Telegram channel ID?</b><br>
Coming soon...

<b>Video Tutorial:</b>
Coming soon...
  
<b>Bugs/Issues</b><br>
If any issues are found it would be appreciated if they are reported, thank you.<br>

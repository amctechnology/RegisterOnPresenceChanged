# registerOnPresenceChanged, registerSetSupportedChannels and registerOnLogout

This project is a sample of using [DaVinci API](https://apidocs.contactcanvas.com/) to register for a Handler when Presence is changed or when the agent is logged out.

registerSetSupportedChannels

The async handler would be called when an agent is logged into a Channel/ DPG. Please note that the following CRM Profile settings to be setup for DPG.

Under Live Presence
Enabled to be set to TRUE 
Use agent id instead of extension to be set to FALSE

With these settings, the channel parameter would contain the extension in the id property of channel.

## Deploy Code

Deploy the two files, [Presence.html] and [davinci-api-1-0-46.js] in any Web server.

## Creating the Application in Studio 

* Open the Creators studio (https://studio.contactcanvas.com) and navigate to the Edit Apps Section 

* Create a new app. 

* Navigate to the configurations of the app you just created and enter the url configuration as per the URL of your Web server. 

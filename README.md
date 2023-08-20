# HiOrg-Public-Calendar-PWA
PWA web app to display a public calendar from HiOrg Server

HiOrg Server (www.hiorg-server.de) offers a tool to create a public calendar. The webpage created over this tool isn't much attractive and not good for showing on a big display on the entrance of a building. So we created our own calendar to display on a big TV. You can find a demo under https://cal.7oi.de/. Therefore we use the public calendar from our friends in Bad Cannstatt. Thanks for this.

## Modify to your own calendar
You can create your own calendar. For his you need a link to your HiOrg Servers JSON file. You can create this link on hiorg-server.de under Kalender -> verknüpfen..., where you can select which events you want to show. Copy the url shown and paste it after fetch in line 45.

![image](https://github.com/gehwissenlos/HiOrg-Public-Calendar-PWA/assets/6155210/ae70140b-30aa-4642-9382-fd8e6a005eb1)

For the PWA you need to change the URL in manifest.json to your own webservers address.

If you want to use a light theme instead of the dark theme you can uncomment the part /* Default (light) theme */ in style.css.

Page refreshes automatically at 0:27 am

# monitoring-scripts
These scripts will help us to notify any event from the servers, ideal for monitoring systems.

# Requirements
- Curl
____________

## Install slack
~~~
 wget -O slack-notify https://raw.githubusercontent.com/jmadrigal07/monitoring-scripts/master/slack/slack-notify
 chmod a+x slack-notify
 mv slack-notify /usr/local/bin/
 ~~~
 ## slack configuration file
 1. Create the /etc/slack-notify.conf
 2. Copy this config and change it with your information.
 ~~~
[general]
token=<YOUR_TOKEN>
user=<BOT NAME>

[network]
socks-proxy=
 ~~~
____________
 
## Install telegram
~~~
 wget -O telegram-notify https://raw.githubusercontent.com/jmadrigal07/monitoring-scripts/master/telegram/telegram-notify
 chmod a+x telegram-notify
 mv telegram-notify /usr/local/bin/
~~~
## Telegram configuration file
1. Create the /etc/telegram-notify.conf
2. Copy this config and change it with your information.
~~~
[general]
api-key=YourAPIKey
user-id=YourUserOrChannelID

[network]
socks-proxy=
~~~

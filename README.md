# Queue Encoder Bot (For Single Users) 
*doesn't work in groups yet pull requests to change that are welcomed*

## With HandBrakeCLI support 
(change `FFMPEG` Variable to [bash handbrakecli.sh](handbrakecli.sh)  instead and configure the script has needed)

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Col-Serra/light-Queue-Enc/tree/main) 🚫

### Variables
`APP_ID` `API_HASH` `BOT_TOKEN`

`OWNER` : Put Id Of Auth Users with a space between it

`THUMBNAIL` : Put telegraph link of a picture for use of Thumbnail.

`ICON` : Put Telegraph link of a picture (png) for use as watermaking image.

`FFMPEG` : Put Your FFMPEG Code with """{}""" as input and output *(Remember to excape the special characters in the case of local deployment to avoid errors)* . (Eg. `ffmpeg -i """{}""" -preset veryfast -vcodec libx265 -crf 27 """{}"""`) *(Also Use this Format When changing code via /set command)*

- [Main Source](https://github.com/1Danish-00/CompressorBot)

### Commands:
```
start - Check If Bot Is Awake
restart - ☢️ Restart Bot 
bash - /bash + command 
eval - Evaluate code
ping - Ping!
get - Get Current ffmpeg code
set - set custom ffmpeg code
status - 🆕 Get bot's status
showthumb - 🖼️ Show Current Thumbnail
cmds - List Available Commands
cancelall - ❌ Clear Cached Downloads & Queued Files
clear - Clear Queued Files
logs - Get Bot Logs
help - Get Detailed Help
```
### Changelogs:
- __[Here](https://col-serra.github.io/light-Queue-Enc/)__ :shipit:

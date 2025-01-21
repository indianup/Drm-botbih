# BATCH EXTRACTOR AND DOWNLOADER

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://telegram.dog/rishavdevkr)

## Deploy To Render                  

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/AnkitShakya95/DRM-Bot-2.git)


## Deploy To Cloud Shell Editor

<a target="/blank" href="https://shell.cloud.google.com/cloudshell/open?cloudshell_git_repo=https://github.com/AnkitShakya95/DRM-Bot-2&tutorial=help/gcloud.md" >
  <img src="https://raw.githubusercontent.com/AnkitShakya95/DRM-Bot-2/main/.github/img/x.svg" alt="Deploy To Cloud Shell Editor" style="width:170px;"></a>

## How to Deploy? 🤔. you can deploy over Heroku or your VPS too.
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/NARUJAT/DRM-Bot-2)

## COMMANDS
### AVAILABLE COMMANDS 
```
/start - check whether the bot is alive 
/ankit - For downloading all app videos such as Physics Wallah, Khan GS, careerwill, E1 Coaching App,
Classplus app and all the other app which is available in you text Files
``` 




[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

# Deploy

Deploy on `VPS`

Easy Method:

- Intall docker-compose
- Fill in the variables in docker-compose.yml file using your favorite text editor or nano 
- Start the container 

```
sudo apt install docker-compose -y
nano docker-compose.yml
sudo docker-compose up --build
```

The hard Way:

- Fill vars in your fork in [this](https://github.com/vasusen-code/SaveRestrictedContentBot/blob/master/main/__init__.py) file as shown in this [picture](https://t.me/MaheshChauhan/36)
- enter all the below commands

```
sudo apt update
sudo apt install ffmpeg git python3-pip
git clone https://gitHub.com/rishavdevkr/maal
cd maal 
pip3 install -r requirements.txt
python3 -m main
```

- if you want bot to be running in background then enter `screen -S srcb` before `python3 -m main` 
- after `python3 -m main`, click ctrl+A, ctrl+D
- if you want to stop bot, then enter `screen -r srcb` and click ctrl+A then press K and enter Y.

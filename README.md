# PinnacleSummer2021G2G
First, install docker virtual machine https://www.docker.com/products/docker-desktop

Within windows or mac command line execute "docker run -p 8050:8050 scrapinghub/splash --max-timeout 3600"

The docker instance can now be run or stopped within the docker application

install pycharm

within the pycharm command line interface execute "pip install scrapy scrapy-splash"

Follow the instructions for configuring scrapy-splash here https://github.com/scrapy-plugins/scrapy-splash

  The settings.py file is actually called default_settings.py and can be found at \Lib\site-packages\scrapy\settings\default_settings.py
  
  The splash server address is "http://localhost:8050/" since the docker instance is hosted on your computer
  
  No need to worry about anything after step 4
  
Replace main.py in pycharm with the main.py you wish to use from this github. Instructions for changing search term/year parameters are included as comments in the script


# flawcode

Source code for the technology podcast

www.flawcode.com

Thank you for listening

# Build instructions:

## Ubuntu install node and npm

    sudo apt-get update
    sudo apt-get install nodejs
    sudo apt-get install npm

## pull project files

    git clone git@github.com:flawcode/website.git

## pull the player and install

    cd core/static
    git clone git@github.com:flawcode/paper-audio-player.git

    npm install -g bower
    bower install paper-audio-player --save


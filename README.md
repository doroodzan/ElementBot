# [ElementBot]

* * *

# Installation

```sh
# Install dependencies.
# Tested on Ubuntu 14.04. For other OSs, check out https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev

# Let's install the bot.
cd $HOME
git clone https://github.com/doroodzan/ElementBot.git
cd mega-shield
chmod +x launch.sh
./launch.sh install
./launch.sh # Enter a phone number & confirmation code.
```

Auto Launch

```

cd mega-shield
killall screen
killall tmux
killall telegram-cli
tmux new-session -s script "bash steady.sh -t"
```

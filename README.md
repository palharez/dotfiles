# My dotfiles
Proudly managed with [rcm/thoughtbot](https://github.com/thoughtbot/rcm)!

### Installation (elementary OS)
```
wget -qO - https://apt.thoughtbot.com/thoughtbot.gpg.key | sudo apt-key add -
echo "deb http://apt.thoughtbot.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/thoughtbot.list
sudo apt update
sudo apt install rcm git fish fonts-ttf-hack
chsh -s $(which fish)
fish
git clone git@github.com:palharez/dotfiles.git .dotfiles
rcup
```
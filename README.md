# Setup dotfiles on Raspberry Pi

#### STEP 1: Login to your Pi

#### STEP 2: Clone the dotfiles from these reporitory

```bash
git clone https://github.com/andsens/homeshick.git $HOME/.homesick/repos/homeshick
~/.homesick/repos/homeshick/bin/homeshick clone mirhec/dotfiles.raspberry
source ~/.bashrc
```

#### STEP 3: Install fish and vim
```bash
# curl -L https://goo.gl/GXHTFj | sudo bash
sudo apt-get install fish vim -y
```

#### Then log out and log in again to apply the changes

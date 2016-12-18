# Setup dotfiles on Uberspace

#### STEP 1: Login to your server

#### STEP 2: Clone the dotfiles from these reporitory

```bash
git clone https://github.com/andsens/homeshick.git $HOME/.homesick/repos/homeshick
~/.homesick/repos/homeshick/bin/homeshick clone mirhec/dotfiles.raspberry
source ~/.bashrc
```

#### STEP 3: Install fish and vim
```bash
# install fish with brew
sudo apt-get update
sudo apt-get install fish vim
```

#### Then log out and log in again to apply the changes

Stateless Workstation Configuration
===================================
This is how I configure a fresh Ubuntu installation for serving me as a workstation.

Usage
-----
After installing a fresh Ubuntu 20.04.3:

```
sudo apt install git ansible
git clone git@github.com:cristiklein/stateless-workstation-config.git
cd stateless-workstation-config
./deploy.sh --ask-become-pass
```

To get the newest version of ansible on Ubuntu: https://www.cyberciti.biz/faq/how-to-install-and-configure-latest-version-of-ansible-on-ubuntu-linux/

Usage on Ubuntu for Windows
---------------------------
```
sudo apt install git ansible
git clone git@github.com:cristiklein/stateless-workstation-config.git
cd stateless-workstation-config
./deploy.sh --ask-become-pass -t wsl
```

Enjoy!

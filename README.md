# workstation-setup
On a fresh [Ubuntu](https://www.ubuntu.com/#download) simply run:
```bash
sudo apt install -y ansible git
sudo ansible-pull -c local -U https://github.com/ajaskier/workstation-setup.git --ask-become-pass
```

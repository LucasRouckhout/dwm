# dwm
My DWM build

## How to install on Ubuntu

With GDM3 you can just run these commands to get DWM as one of the possible sessions.

```bash
sudo apt-get install build-essential libx11-dev libxinerama-dev sharutils suckless-tools
```

Then `cd` into this repo and run.

```bash
sudo make clean install
```

Then run

```bash
sudo apt install dwm
sudo cp /usr/share/xsessions/dwm.desktop{,.bak}
sudo apt purge dwm
sudo mv /usr/share/xsessions/dwm.desktop{.bak,}
```

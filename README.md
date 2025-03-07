<div align='center'>
<img src='./icons/logo-full.png' width='128px'> 
<h1>Pi-Forge the Pi-Ware continuation</h1>
Pi-Forge is a community-driven continuation of Pi-Ware. <a href="https://github.com/piware14/pi-ware">Pi-Ware</a> is an app store inspired by Botspots <a href="https://github.com/Botspot/pi-apps">pi-apps</a> for the Raspberry Pi that allows you to install apps that you generally can't get from the official repos and/or without an extra amount of work.
  
# NEW:

We have added some new stuff go have a look!

To learn more vist our <a href="https://github.com/G265Dev/Pi-Forge/wiki/New-Stuff" alt="Pi-Forge wiki">wiki</a>!
  
# Links:

**Join our Discord server**:

[![Pi-Ware Discord server](https://img.shields.io/discord/840124418528378881?color=7289da&label=Discord%20Server&logo=discord&style=flat-square)](https://discord.gg/BU8F6D8X6s)

**Look at our wiki**

<a href="https://github.com/G265Dev/Pi-Forge/wiki" alt="Pi-Forge wiki">The Pi-Forge wiki</a>

</div>
  
# How to install and use Pi-Forge

## Install Pi-Forge
```sh
sudo apt update && sudo apt upgrade -y
sudo apt install python3 -y
sudo apt install python3-pip -y
sudo apt install python3-tk -y
sudo apt install python3-ttkthemes -y
sudo apt install python3-screeninfo -y
git clone https://github.com/G265Dev/Pi-Forge.git
mv Pi-Forge pi-ware
cd pi-ware
bash install
```

## Update Pi-Forge
Pi-Forge will automatically fetch and install updates, and tell you to restart it to apply them.

If you want to force update Pi-Forge, run
```sh
pi-ware --update --force
```

## Uninstall Pi-Forge
```sh
cd $HOME/pi-ware
bash uninstall
```

Thanks to https://chatgpt.com/ for providing our logo!

Enjoy Pi-Forge

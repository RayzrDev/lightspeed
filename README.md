# lightspeed

> Server files for the LightspeedMC (RayzrDev) Minecraft server

This repo contains the majority of the plugin & config files for the LightspeedMC Minecraft server. Using git for this means proper version control when updating configs, easy local setups if you want to debug issues on the live server without interruptions, and community collaboration on fixing configuration errors, adding/tweaking plugins, and more.

## Play

If you want to play the [offical LightspeedMC server](https://mc.rayzr.dev/), feel free to hop on:

Discord: https://rayzr.dev/join
Minecraft: `mc.rayzr.dev` (1.16.1)

## Setup

If, instead, you want to do your own local setup of this server either for collaboration or debugging purposes, you will need a few things first:

0. Basic terminal knowledge
1. Java 8
2. Git
3. Tuinity 1.16

```bash
# clone the repo
git clone https://github.com/RayzrDev/lightspeed.git
cd lightspeed
# copy in Tuinity JAR
cp path/to/tuinity-paperclip.jar .
# run the server
./start.sh
```

From there, feel free to tweak things to your liking! Any PRs are greatly appreciated, with the limitation that premium plugins cannot be included (for legal reasons), and also that you please do your best to `.gitignore` any files which are more just storage and less config, such as playerdata or world files.

## Join Me
[![Discord Badge](https://github.com/Rayzr522/ProjectResources/raw/master/RayzrDev/badge-small.png)](https://rayzr.dev/join)

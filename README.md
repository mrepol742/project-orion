# project-orion [![Project Orion CI](https://github.com/mrepol742/project-orion/actions/workflows/npm.yml/badge.svg)](https://github.com/mrepol742/project-orion/actions/workflows/npm.yml)

<img src="https://mrepol742.github.io/images/orion-banner.png" align="right" width="300px"/>

Meet the lightning-fast Facebook Messenger chatbot, seamlessly managing multiple accounts with access to 271 commands and more.

> **⚠️ DEPRECATED:** This project is no longer actively maintained. Please use with caution and consider alternatives for production use.

> **Looking for a maintained alternative?**  
> The successor to Orion is now available for WhatsApp and Telegram. Check the [official repository](https://github.com/mrepol742/project-canis) for more details.

## Pre-requisites
- Install [Node.js](https://nodejs.org/en/) version 20.x.x

    For better performance i require hosting this program on following platforms
    - Digital Ocean (tested)
    - Amazon Web Services
    - Microsoft Azure (tested)
    - Google Cloud
    - Replit (tested)
    - Termux (tested)

## Requirements
- 1GB Disk Space
- 1GB RAM or VRAM
- 1 or more CPU/vCPU core <br>

  For vm and vps:

  - Ubuntu, Mint or Arch OS
  - Xcfe for DE
  - Windows XRDP


## Getting started
- Fork the repository  <br>
  https://github.com/mrepol742/project-orion/fork
- Clone fork the repository
  ```sh
  # using https
  git clone https://github.com/<your-username>/project-orion
  
  # using ssh
  git clone git@github.com:<your-username>/project-orion
  ```
- Install dependencies
  ```sh
  cd project-orion && npm run setup

  # for linux os that uses apt please run
  npm run setup_extra
  ```
- Add your Instance
  >There is different ways to add your account instance usually it depends on how you run this program

  - local machine, virtual machine or vps
     ```sh
     # linux
     mkdir data
     mkdir cookies
     touch /data/cookies/instance.bin
     nano /data/cookies/instance.bin
     # then paste your account instance and save

     # windows & macos
     open file explorer (or any similar app)
     navigate to the project directory
     create the following folders and file.
     /data/cookies/instance.bin
     open instance.bin using any text editor 
     paste your account instance and save
     ```

  - render or any similar platform where u cant edit the deployed files
     ```sh
     open the environment section of the site
     click add new env
     name it `APP_STATE`
     paste your account instance in value input
     then save
     ```
- Run the project
  ```sh
  # for linux
  npm run start

  # other than linux
  npm run start_win

  # for dev
  npm run dev
  ```
- Eslint
  ```sh
  npm run eslint ./
  ```

## Common Problems & Fixes
- Module not found
  ```sh
  # run 
  npm run setup
  ```
- Problems related to .env
  ```sh
  rm -rf .env
  # just delete the .env
  # and start again
  ```
## Contribute
Code contributions are welcome! Please commit any pull requests against the master branch. Security audits and feedback are welcome. Please open an issue or email us privately if the report is sensitive in nature.

## License
```
Copyright (c) 2022 Melvin Jones
  
  Orion is free software: you can redistribute it and/or modify it 
  under the terms of the GNU General Public License as published by 
  the Free Software Foundation, version 3 of the License
  
  without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. 
  See the GNU General Public License for more details.
  
  You should have received a copy of the GNU General Public License along with Orion. If not, see <https://www.gnu.org/licenses/>.
 ```
<br>
# RESILINK_Raspberry
# Script for installing and deploying an instance of a RESILINK server on a Raspberry

The purpose of this script is to automatically deploy a ready-to-use Node.js server on a Raspberry Pi (or any Debian-like system).

## Main features

- Complete system update (apt update & upgrade)
- Installation of essential dependencies:
 - MongoDB (database)
 - Node. js & npm (JavaScript environment)
 - Avahi (mDNS name resolution)
 - Git (repository cloning)
 - curl & gnupg (API management and installation keys)
- Configuration of MongoDB with the collections and entities required to run the application
- Project cloning via
- Installation of Node.js project dependencies
- Creation of systemd services to automatically start :
  - the MongoDB server
 - the Node.js server
- Automatic launch of the server on system startup

## Prerequisites

- Debian system (e.g. Raspberry Pi OS)
- Active Internet connection ( Information verified in the script )

## Usage

Go to the .sh file folder in the terminal and simply run the script with the commands

 sudo chmod +x install_and_run.sh (gives the right to run the file)
./install_and_run.sh

Translated with DeepL.com (free version)

# fuscus_tools - A Fuscus installer

## Overview
This implements a brief installation script streamlining the installation of Fuscus - a Python implementation of a temperature controller for BrewPi. This attempts to implement most of the procedure documented in notes.md in the original Fuscus repo, with the exceptions noted below.

**Implemented:**
* Add the 'fuscus' user
* Add 'fuscus' to sudoers
* Set up the appropriate visudo line
* Download the latest version of the code from your repo on GitHub

**Not part of script - bust be done manually:**
* Setup of Raspberry Pi, installation of BrewPi, etc.
* Launch Fuscus
* Configure Fuscus (Update/create fuscus.ini)
* Set up a crontab entry to launch Fuscus




## Usage
The full Fuscus installation notes are located at https://github.com/andrewerrington/fuscus/blob/master/docs/notes.md and are a highly recommended read.

Once you've read through them, follow the instructions here:
https://github.com/thorrak/fuscus_tools/blob/master/usage.md



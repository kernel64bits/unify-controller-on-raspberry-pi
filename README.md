# unify-controller-on-raspberry-pi

## Introduction
Automate the installation of a unifi network controller on a raspberry Pi using Ansible. 

It was pretty hard to find a MongoDB version compatible with my Raspberry Model 3B, so I finally took inspiration from ![this tutoriak](https://pimylifeup.com/rasberry-pi-unifi/).

## Pre-requisite

### Raspberry Pi
I'm using a Raspberry model 3B running the latest available raspbian version.

### On your computer
Ansible & ansible-playbook installed

## Quick start
1. Set your raspberri pi IP address in inventory.ini
2. Run `ansible-playbook -i inventory.ini install.yaml`




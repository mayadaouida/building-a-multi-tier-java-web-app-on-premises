# Building a Multi-Tier Java Web Application On-Premises

## Project Overview
This repository contains the Vagrant configuration for the manual provisioning setup of the VProfile multi-tier Java web application in a local VirtualBox environment.

## Environment
- Host OS: Windows
- Virtualization: Oracle VirtualBox
- VM provisioning and management: Vagrant

## Project Files
- `Vagrantfile`: Defines the virtual machines and their configuration.
- `VprofileProjectSetupWindowsAndMacIntel.pdf`: Project setup guide.

## Setup
1. Install Oracle VirtualBox and Vagrant.
2. Review the `Vagrantfile` and the setup guide.
3. Open a terminal in the project directory.
4. Run `vagrant up` to create and start the virtual machines.
5. Run `vagrant status` to check their status.
6. Use `vagrant halt` to stop the virtual machines when finished.

## Notes
This repository documents the local manual provisioning setup. Application functionality and service connectivity should be verified separately.


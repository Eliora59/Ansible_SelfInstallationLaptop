# Self Installation with Ansible
## How it works
 
We download a minimalist bash script that i host on my website to install and update ansible on the latest version. This makes it possible to install everything with only one command.

:warning: This allows us to fully use Ansible from the package manager without being disturbed by it's own update and without pip3 manager.

Then it will launch the auto install with ansible-pull.

## How to use

``` 
wget -O - install.overcomputing.net/init | bash 
```
#### OR
```
wget -O - https://raw.githubusercontent.com/Eliora59/SelfInstall/main/init | bash
```
## To do :
* Find solution for proprietary software
    * Packet Tracer
    * PyCharm
    * Discord
    * VMware Workstation
        * ~~To try: Download software with CI/CD or manually download and vault it to avoid some proprietary issues~~
        * ~~To try: Download and installation from the executed playbook~~
        * Download and compress it (Try with git-lfs.github.com for file more large than 100 MB) 
* Add IOS image
* Vault "files" directory
* https://www.kite.com/

## To improve
* Repository Visual Studio Code, to use modules like _apt_key_ and _apt_repository_ instead of module _shell_ with commands that microsoft gives.
* Repository GNS3
* Customizing desktop environment
test

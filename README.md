# Whonix - I2P 
####This Repo contains various files related to my Whonix-I2P Development/Porting
#Disclaimer!
This Repo is just a dumping ground for all sort of files, they may not work or/and could break your system !!
As soon as everything works  I will delete this repo and create a proper one with instructions...
#### Note :
###			Currently it's not working , Bug reports/PR's welcome
##Testing/Setup
###[Qubes OS only]
- Clone your existing Whonix Gateway and Worksation Templates
- Download the Repo to your (cloned) Whonix GW Template
- Run `anon-i2p-gw-template-config` as root in the (cloned) Whonix GW template
- Wait until it finishes after that power the Template down and create a new ProxyVM (eg. sys-i2p) from 
the (cloned) Whonix GW Template.
Start the ProxyVM (sys-i2p) and run `anon-i2p-gw-proxyvm-config` as root , reboot the ProxyVM (sys-i2p)
- Download the Repo to your (cloned) Whonix WS Template and run `anon-i2p-ws-template-config`
- Now you can run `sudo i2p-launcher start &` on your ProxyVM (sys-i2p) to start the I2P Router 


`sudo tail -f /var/log/i2p/wrapper.log` for debuging

###Known Issues/Bugs

- currently disabled console port redirection to the Workstation ( use lynx or iceweasel on the GW to manage i2p or via config)
- DNS could give some Issues
- long startup time (just get a cup of coffee)


###More to come ...

# Centos Installers
Various scripts for installing additional packages on CentOS 6.  

Some scripts may work for additional versions or platforms and are specified in the script headers.

#Installation/Execution
Scripts can be executed directly or downloaded and run. All scripts are intended to be installed from the root user.

## Directly
```bash
su -
curl -L $(RAW_SCRIPT_URL) | bash
```

## Download Entire Package
```bash
wget -O /tmp/centos_installers.zip https://github.com/subfission/centos-installers/archive/master.zip
unzip -d /tmp /tmp/centos_installers.zip && rm -f /tmp/centos_installers.zip
mv /tmp/centos-installers-master /centos-installers
cd /centos-installers/scripts
```

# Tailored IoT application Template for ctrlX CORE

## Why?

The idea is to create a "Template" containing all the main IoT tools for industrial purposes that the use may want to use. All the apps have their own configuration files exposed. 

## Template content:

- influxdb
- node-red
- mongodb
- python with the most used data analysis libraries and opencv


## Building 

First clone the REPO and enter the directory. 

### AMD64

Install snapcraft:

    sudo snap install snapcraft
    
Install multipass:

    sudo snap install multipass
    
Build:

    snapcraft 


### arm64 (on a native arm64 device)

Install snapcraft:

    sudo snap install snapcraft
    
Install LXD:

    sudo snap install lxd
    
Initialize LXD:

    sudo lxd init
    
Build:

    snapcraft --use-lxd
    
### Remote-Build (both platforms but remotely and publicly available)

Install snapcraft:

    sudo snap install snapcraft
    

Build:

    snapcraft remote-biuld


# Tailored IoT application Template for ctrlX CORE

## Why?

The idea is to create a "Template" contining all the main IoT tools for industrial purposes that the use may want to use. All the apps have their own configuration files exposed. 


## Building 

First clone the REPO and enter the directory. 

### AMD64

Install snapcraft:

    sudo snap install snapcraft
    
Install multipass:

    sudo snap install multipass
    
Build:

    snapcraft 


### arm64

Install snapcraft:

    sudo snap install snapcraft
    
Install LXD:

    sudo snap install multipass
    
Initialize LXD:

    sudo lxd init
    
Build:

    snapcraft --use-lxd

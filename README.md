# Node-RED Snap template


## Modding

Modify files "flows.json" and "settings.js" in scripts/conf to customize the node-red content. Nodes to be preinstalled could be placed in the snapcraft.yaml file.

## Building - native ubuntu

    sudo chmod 777 -R *
    sudo snap install multipass
    sudo snap install snapcraft --classic
    snapcraft
    

## Building - VM
   
    sudo chmod 777 -R *
    sudo snap install lxd
    sudo lxd init -> confirm all defaults
    snapcraft --use-lxd
    
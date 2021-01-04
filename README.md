# tutorial-caseProxmoxPFsenseFrenas

Passos

Instalar HyperVisor Proxmox
Configurar interface brigde com a interface eth0

Configurar VSwitch
$ apt install openvswitch-switch

Instalar VM PFSense
Associar a VM a Interface vmbr0 (Bridge-Eth0)
Associar a VM a Interface vmbr1 (VSwitch)

Instalar VM com o FreeNas
Associar a VM a Interface vmbr1 (VSwitch)

Instalar VM Linux Server
Associar a VM a Interface vmbr1 (VSwitch)

Instalar VM Windows Server
Associar a VM a Interface vmbr1 (VSwitch)

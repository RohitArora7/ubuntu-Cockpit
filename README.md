# ubuntu-Cockpit

virsh list --all 

/var/lib/libvirt/images



virt-clone \
   --original ubuntu20.04 \
   --name ubuntu20.04-clone_247\
   --file /var/lib/libvirt/images/ubuntu20.04-clone_247.qcow2
   
   
   vim /etc/netplan/00-in
   
   sudo netplan apply

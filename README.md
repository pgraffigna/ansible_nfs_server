# ansible_nfs_server

Playbook para configurar un servidor NFS + configuracion de firewall

roles:
- firewall
- nfs

---
Para que el cliente pueda acceder a los recursos necesita hacer

apt update && sudo apt install -y nfs-common
mkdir -p /mnt/TEST
mount IP_SERVIDOR:COMPARTIDA  /mnt/TEST

		 

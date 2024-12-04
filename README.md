## Ambiente homelab:
Neste artigo, vou demonstrar como administar um ambiente proxmox.<br>
Nesse ambiente, usamos as seguintes versões:

> **Sistema Operacional:** Debian 12<br>
> **Proxmox:** 8.3.0<br>
> **Templates:** Ubuntu 20.04 e Rocky Linux

## Criar um ambiente virtualizado no proxmox:
```bash
apt install python3.11-venv
source ~/proxmoxer-venv/bin/activate
python3.11-venv
python3 -m venv ~/proxmoxer-venv
pip install proxmoxer
pip install requests
```
## Acessar o ambiente virtualizado:
```bash
python3 -m venv ~/proxmoxer-venv
```
## Instalar as dependencias no bastion:
```bash
apt install ansible -y
apt install python3-pip -y
pip install --upgrade ansible
pip3 install proxmoxer
ansible-galaxy collection install community.general --force
```

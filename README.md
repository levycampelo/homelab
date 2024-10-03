## Ambiente homelab:
Neste artigo, vou demonstrar como administar um ambiente proxmox.<br>
Nesse ambiente, usamos as seguintes versões:

> **Sistema Operacional:** Debian 12<br>
> **Imagem:** Ubuntu 20.04.6<br>
> **Proxmox:** 8.2.7

## Criar um ambiente virtualizado no proxmox:
python3.11-venv<br>
python3 -m venv ~/proxmoxer-venv<br>
pip install proxmoxer<br>
pip install requests<br>

## Acessar o ambiente virtualizado:
python3 -m venv ~/proxmoxer-venv

## Instalar dependencias no bastion:
apt install ansible -y<br>
apt install python3-pip -y<br>
pip install --upgrade ansible<br>
pip3 install proxmoxer<br>
ansible-galaxy collection install community.general --force<br>


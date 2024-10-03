### Instalar dependencias
apt install ansible -y<br>
apt install python3-pip -y<br>
pip install --upgrade ansible<br>
pip3 install proxmoxer<br>
ansible-galaxy collection install community.general --force<br>

### Criar um ambiente virtualizado no proxmox
python3.11-venv
python3 -m venv ~/proxmoxer-venv
pip install proxmoxer

# acessar o ambiente virtualizado
python3 -m venv ~/proxmoxer-venv
pip install requests

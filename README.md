# Kubernetes the hard way - Automation

Dieses Repo dient dazu die K8s zu lernen und zu deployen, aber auch gleichzeitig Ansible Automation zu erlernen.
Dafür wird, während ich K8s the hard way durchlaufe, zeitgleich alles per Ansible automatisiert.

## Hardware

- Dell OptiPlex 5060
- 6 CPU Kerne (i5-8500 3ghz)
- 16GB RAM
- 240GB SSD

## Betriebssystem

- Ubuntu 24.04 LTS

## Vorbereitung

### Git Repo clonen

### Python Installieren

```bash
sudo apt install python3-pip
sudo apt install python3.12-venv
python3 -m venv .venv
source .venv/bin/activate
```

### Ansible & Co installieren

```bash
pip install -r requirements.txt

oder 

pip install ansible
```

## Ansible Automation

## Apt Update, Upgrade, Install

sudo apt -y install bridge-utils cpu-checker libvirt-clients libvirt-daemon qemu-kvm
kvm-ok


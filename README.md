# ansible-nvidia-docker2
Ansible playbook to install Nvidia driver, Docker CE and nvidia-docker2 on an Ubuntu server. This has not been tested on other operating systems.

## Details

* Nvidia driver 384.111
* Nvidia CUDA 8.0.61
* Docker CE
* nvidia-docker2

## Usage

Set your username in the `vars` bit of the `playbook.yml` file and add your servers to the `inventory` file. Then simply run the playbook.

```ansible-playbook -i inventory playbook.yml```
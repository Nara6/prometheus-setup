# prometheus-setup
## To set up 
* Make sure your computer have already install ansible
* Make sure you have add ssh key to your VM
* Config inventory point to your IP address
## Command
### Install prometheus
```sh
   ansible-playbook -i inventory prometheus-installation-playbook.yml
   ```
### Install node exporter
```sh
   ansible-playbook -i inventory node-exporter-installation-playbook.yml
   ```

## Automation

The automation project uses Ansible to perform end-to-end installations and configurations
for each SearchStack.ai service. The deployment should work for any CentOS-based Linux
system assuming you can SSH into a remote as root. The following environments
have been tested:

* Amazon AWS - Linux (CentOS)
* VirtualBox - Linux (CentOS)

# Prerequisites 

* None

## Installation & Configuration Steps

1. Install Docker.

2. Install VirtualBox.

        $ sudo apt install virtualbox -y

3. Install Ansible.

        $ sudo apt install ansible -y

4. Install Vagrant.

        $ sudo apt install vagrant -y
        $ vagrant plugin install vagrant-vbguest
        $ vagrant plugin install vagrant-scp

5. Install Minio. TODO

6. Configure /etc/hosts. TODO

7. Clone the automation project.

        $ cd $SEARCHSTACK_AI_HOME
        $ git clone https://github.com/GastonGonzalez/greenrush-automation.git
        $ cd greenrush-automation

## Next Up

Setup the [Document Processing](02-document-processor.md) service.
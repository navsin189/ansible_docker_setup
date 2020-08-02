# ansible_docker_setup
installed and configured docker via ansible
ansible.cfg is the configuration file of ansible.
host_list.txt contains the list of host with their login username and password.
yum.yml is the main ansible playbook used to install and configure docker.
I used docker's stable version due to the issue of --nobest in community edition of RedHat8.
Signed in through my login id of docker hub to pull the images.

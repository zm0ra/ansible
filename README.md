# Kubernates installation playbook

hosts - define each node in k8s cluster:
* ansible_host = IP of node
* ansible_user = user for ansible to use
* ansible_host_alias = host alias for /etc/hosts generator + used in k8s cluster
  
usage:
  * ansible-playbook -i k8s/hosts k8s/install-k8s.yml

# Kubernates installation playbook

hosts - define each node in k8s cluster:
* ansible_host = IP of node
* ansible_user = user for ansible to use
* ansible_host_alias = host alias for /etc/hosts generator + used in k8s cluster
  
usage:
  * docker run -v ~/.ssh/:/root/.ssh/ --name ansible-k8s -it zm0ra/ansible-k8s
  * ansible-playbook -i hosts install-k8s.yml

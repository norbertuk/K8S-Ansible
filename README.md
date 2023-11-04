# K8S-Ansible

This playbook installs K8S kubelet, kubeadm, kubectl V1.27.
Container runtime is Containerd.

To run the playbokk specify the target as shown: 
ansible-playbook user.yml --extra-vars "target=<your_hostname>"

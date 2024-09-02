 ansible-playbook -i inventory.ini -e ansible_user=ec2-user -e ansible_password=DevOps321 01-ping.yaml
above command is to play playbook
ansible-playbook -i inventory.ini -e ansible_user=ec2-user -e ansible_password=DevOps321 09-vars-from-args.yaml -e "NAME=firdose GREETING=night"
above command is to take arguments from outside

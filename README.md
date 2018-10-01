Ansible playbook which install list of packages from external file. Using ec2.py as dynamic host inventory.
  
  Usage: `ansible-playbook site.yml -i ec2.py -e tag="tagname" -e "@roles/common/defaults/packages.json"`<br/>
  This command will install list of packages from ***packages.json*** file to all hosts with ec2 tag ***tagname***

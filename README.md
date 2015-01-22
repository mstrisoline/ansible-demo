# ansible-demo
Ansible Demo Repository

## How To Use
Make sure you have ansible installed you can reffer to their installation here: http://docs.ansible.com/intro_installation.html

You will also need Oracle Java 7 update 67  tar.gz which you can download from Oracle

It will also by default need to be placed in the /opt/ansible_store/java directory on the filesystem
* This is done because we can't simply wget it from the web

Update the `hosts` file to have a usable host and you should be good to run ansible

`ansible-playbook -u $USER -k -K -s -i hosts playbooks/jenkins.yml`

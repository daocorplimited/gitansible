# gitansible

## GitOps way to run

1. Just commit your new code to the main branch and it will be automatically delivered.

## Manual way from a local machine

1. Have Ansible and all keys installed
1. Edit the _inventory.ini_ file to update destination host addresses and website folders.
1. Run: 

        $ ansible-playbook -i inventory.ini massive.yaml -vv
# Ansible Collection - joget.iac

Documentation for the collection.

## Install
```
ansible-galaxy collection install git+https://github.com/simhead/joget#joget/iac,main
ansible-playbook joget.iac.usct_deploy -i /iac-run-dir/output/inventory
     e.g. ansible-playbook joget.iac.usct_deploy -i /home/ubuntu/ally/tmp/output/joget-app3/inventory

```

## Uninstall
```
ansible-galaxy collection install git+https://github.com/simhead/joget#joget/iac,main
ansible-playbook joget.iac.usct_undeploy -i /home/ubuntu/ally/tmp/output/joget-app3/inventory
ansible-playbook joget.iac.oci_cleanup -i /home/ubuntu/ally/tmp/output/joget-app3/inventory
```
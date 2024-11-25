# Ansible Collection - joget.iac

Documentation for the collection.

## Install
```
ansible-galaxy collection install git+https://github.com/simhead/joget#joget/iac,main
ansible-playbook joget.iac.joget_deploy -i /iac-run-dir/output/inventory
     e.g. ansible-playbook joget.iac.joget_deploy -i /home/ubuntu/ally/tmp/output/joget-app2/inventory

```

## Uninstall
```
ansible-galaxy collection install git+https://github.com/simhead/joget#joget/iac,main
ansible-playbook joget.iac.joget_undeploy -i /home/ubuntu/ally/tmp/output/joget-app2/inventory
ansible-playbook joget.iac.oci_cleanup -i /home/ubuntu/ally/tmp/output/joget-app2/inventory
```
# Execution Environment

EE for running this collection in AAP.

To build this EE:

```
cp -i extensions/execution_environment/secrets.yml.template extensions/execution_environment/secrets.yml
nano extensions/execution_environment/secrets.yml

ansible-playbook -e @extensions/execution_environment/secrets.yml extensions/execution_environment/build_ee.yml
```

# aviOs
Prerequisites:
- Make sure Ansible is installed
- Make sure the Avi SDK is installed with appropriate version( pip list | grep avi ):
	- pip install avisdk --upgrade
        - ansible-galaxy install -f avinetworks.avisdk
- Make sure Avi Controller is reachable

Use the ansible playbook to
- modified the default cloud as an OpenStack cloud with the parameters in vars/params.yml

Example:
ansible-playbook aviOs.yml

Script has been tested against:
- Avi 17.2.14, 18.1.5
- Ansible 2.7.0

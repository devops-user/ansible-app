#ansible-app

This application for calculate

1. You need start with preparation server:
	# **ansible-playbook -i inventory/prod Initial_setup.yml**

2. The second step deploying the application on a server:
	# ansible-playbook -i inventory/prod Deploy_goapp.yml

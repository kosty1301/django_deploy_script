# django_deploy_script
Small script for the django project deploy in clear server

## Quick start
```sh
wget https://github.com/kosty1301/django_deploy_script/blob/main/django_deploy.sh
sudo chmod +x django_deploy.sh
./django_deploy.sh <url for your git repo...>
```
### Use this script only on a clean server otherwise you may lose your nginx settings!
* the old nginx configuration will be moved to the home directory

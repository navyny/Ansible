# Installing Ansible on MAC in a Virtualenv


Pre-reqs:
1-Upgrade pip3 to latest "python3 -m pip install --upgrade pip"
2-Check version "pip3 --version"

When I installed Ansible using "pip3 install ansible" & try "ansible --version" there was COMMAND NOT FOUND
though I could see ansible installed location using "pip3 show ansible"

Clearing cache using "hash -r" did not help

So I installed Ansible in a Virtualenv

```
python3 -m pip install virtualenv  #installing virtualenv module

python3 -m virtualenv <ansiblevenv>  #Creating a virtual ENV for Ansible

source <ansiblevenv>/bin/activate   #virtual env needs to be activated

python3 -m pip install ansible

```






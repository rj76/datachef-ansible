Datachef ansible playbook
==========================

Install
--------

`$ mkvirtualenv datachef`
`$ pip install -r requirements.txt`


Usage
------

Run all tasks:

`$ ansible-playbook -i hosts provision-aws.yml`

Simple upgrade:

`$ ansible-playbook -i hosts provision-aws.yml -t base`

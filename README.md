

Install *docker* and *docker-compose*:

    ansible-playbook -i inventory -s -k -u root docker.yml


Install *nodejs*

    ansible-playbook -i inventory -s -k -u root nodejs.yml

Install *ruby*

    ansible-galaxy install geerlingguy.ruby -p roles
    ansible-playbook -i inventory -s -k -u root ruby.yml

# playbook

sudo pacman -S git python3 python-ansible
git clone https://github.com/CuriousAvenger/playbook
cd playbook
ansible-galaxy install -r requirements.txt
ansible-playbook playbook.yml
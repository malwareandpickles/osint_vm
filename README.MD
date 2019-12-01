This is an Ansible script based on the book Intel Techniques by Michael Bazzell. The main goal is to speed up the building of an OSINT Virtual Machine.

Not in any way associated with the author, however bought the latest book and found it really interesting.

Instructions:

1. Install the latest version of Xubuntu and configure in Virtualbox.
   (https://xubuntu.org/download)
2. Make sure to create the user named 'osint'.
3. Install some packages 'apt-get install ansible git'
4. Clone or download this repo.
5. Install by running 'ansible-playbook playbook2.yml --ask-sudo-pass'


To be completed:

Automating the whole build including spinning up Linux distro

Adding configuration of Firefox (Installing addons / making changes)

Adding a few more additional tools.

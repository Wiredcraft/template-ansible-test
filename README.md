## Why this test

This simple test is meant to evaluate:

- your tech skills,
- your ability to communicate through GH tickets and Slack,
- your ability to learn new technology (if you already know Ansible, please kindly let me know @zbal to I can offer you a more suitable test)

You mentioned that you don't know (yet) Ansible, we like Ansible, so ... well ... Ansible it is for you !

If you have not received your invite for [Slack](https://slack.com) please contact me.

## Guidelines

The guidelines are especially loose as I want you to drive some discussion to get some of the missing information.

1. Get a base Ubuntu 14.04 Vagrant box (need [VirtualBox](https://www.virtualbox.org/) and [Vagrant](https://www.vagrantup.com/)) - then go in the `./vagrant` folder and run `vagrant up`.
2. Get [Ansible](http://docs.ansible.com/)
3. Prepare a playbook following the [best practices](http://docs.ansible.com/ansible/playbooks_best_practices.html) for the file system structure, and get this file structure committed/pushed over to github.
4. Actions:

  - Update apt, add sysstat/htop.
  - Add users + sudo users.
  - Install php + php-fpm + mysql + nginx.
  - Install and setup wordpress.
  - Get the install page displayed when you access the IP address of your vagrant box.

5. Please push your code to this repository.

You may want to use [Ansible roles from the galaxy](https://galaxy.ansible.com) to speed up some of the setup of the various services. 

Please create your own role (name it `wiredcraft-default`) to install the various packages, users and sudo. Create a second role called `wiredcraft-wordpress` to install and customize wordpress. 

*Note*: do not push your roles to the Ansible Galaxy. 

## Reminder / Notes

As a reminder and extra notes:

- If you don't know, ask questions.
- If you are unclear, ask questions.
- Document your code / playbooks.
- Fill your tickets with the relevant questions and details so we can provide you with useful feedback.
- Impress me ;)
- It shouldn't take you more than half a day.
- Please complete the test within a week - if you can't please let me know in advance.


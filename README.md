# drupal-pantheon-devbox
A box that aims to emulate the Pantheon architecture for local development

Starting point forked from https://github.com/craychee/no-excuses-drupal, thank you!

## Prerequisites
* Vagrant
* VirtualBox
* Ansible

## Instructions
Copy the /ansible directory and Vagrantfile into the root of your Drupal project.

Then, in the root, run `vagrant up`

At the moment, you will need to manually import the database and files.

Read ansible/vars/all.yml to see database settings.

After the import, go to http://192.168.33.99 to view your site.

## To do
* Drush aliases
* Script to pull down database/files with Terminus/Drush
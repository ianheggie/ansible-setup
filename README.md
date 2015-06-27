# outfitting_with_ansible
Oufitting with ansible - Ansible outfit and notes for provisioining ruby, rails and django projects

** NOTE: This is a early WORK IN PROGRESS and will undoubtedly change in the future, possibly breaking backwards compatibility. **

## Installation
Install as a sub module and then symlink in the appropriate files: 
```
mkdir -p outfit
git submodule add https://github.com/ianheggie/outfitting_with_ansible.git outfit/outfitting_with_ansible
cd outfit/outfitting_with_ansible
./install.sh
```

You can use the `outfit-version.txt` later on to review changes in this project to decide if you want to incorporate them.

### Install as git sub module and sym link in
```
mkdir outfit


## Layout

* outfit - All my ansible provisioning code goes under a directory called `outfit`
  * requirements.yml - list of roles I have used with various projects, with comments when/why
  * bin - includes dev bootstrap and ansible comand wrappers

## Resources and Thanks to

* Matt Jaynes who wrote a good comparison book [https://valdhaus.co/books/taste-test-puppet-chef-salt-stack-ansible.html][Taste Test: Puppet, Chef, SaltStack, Ansible (and Docker)] - I looked at puppet and chef, tried saltstack and have settled on ansible
* https://github.com/theodo/list-ansible-roles/blob/master/README.md - a starting point for my own list

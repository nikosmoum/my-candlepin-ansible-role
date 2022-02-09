# My candlepin Ansible role
This is a custom ansible role with a list of miscellaneous tasks I find useful that can be run at the tail-end of the provisioning of a candlepin vagrant vm.
This conforms with the instructions provided [here](https://github.com/candlepin/candlepin/tree/master/vagrant#custom-provisioning-tasks).

## How to use
* Checkout candlepin from https://github.com/candlepin/candlepin
* `cd` to the \<root\>/vagrant/roles/ directory of the checkout, and clone this repo into it in a folder called `candlepin_dev`: `git clone git@github.com:nikosmoum/my-candlepin-ansible-role.git candlepin_dev`.
* Go back to the \<root\> directory and run `vagrant up`
This should provision a Centos vm using vagrant and ansible, where the last ansible tasks run will be the ones in this repo.

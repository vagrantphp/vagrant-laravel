# vagrant-symfony

A local development environement built using [Vagrant](http://vagrantup.com/) and [Virtualbox](https://www.virtualbox.org/) using puppet and command line provisioning. This will build a local environment for you to start building your own symfony application. 

## Tools

### Vagrant

Create and configure lightweight, reproducible, and portable development environments. A command line wrapper for VirtualBox.

### Puppet

Puppet manages your servers: describe machine configurations in an easy-to-read declarative language, and Puppet will bring your systems into the desired state and keep them there.


## Installation

Install Vagrant + Virtualbox then run the following commands:

 	git clone git@github.com:vagrantphp/vagrant-symfony.git
	cd vagrant-symfony
	vagrant up


Configure the symfony YAML file to match your local configuration

	/vagrant/www/symfony/app/config/parameters.yml
	

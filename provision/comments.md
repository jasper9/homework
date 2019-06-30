
### Notes
- The homework suggested using `runit` from PackageCloud. I first used the PackageCloud role to install this, however I found the role `gotansible.runit` which seemed like a way more efficient route as it both installs runit AND can create a service via tasks.

- I almost went with a role for nginx also, however using the supplied nginx.conf seemed like a quicker route since I was already familiar with setting up the configuration.

- The cert is expired I noticed.  I doubt this is part of the homework since we're ignoring verification with the -k flag

## Running

### On MacOS:
brew cask install virtualbox
brew cask install vagrant
brew cask install vagrant-manager
pip3.7 install ansible

### On Ubuntu:


### Required:
ansible-galaxy install -p roles gotansible.runit

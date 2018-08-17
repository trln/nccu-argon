## Requirements

[VM](https://www.virtualbox.org/)

[Vagrant](https://www.vagrantup.com/docs/installation/)

## Building the VM

1. Install VM and Vagrant

2. Clone this repository

3. `cd TRLN_Discovery_UNC`

4. `vagrant up`

5. `vagrant ssh` -> `cd /vagrant` -> `cd unc_blacklight`


## Start up your application:

 `bundle exec puma -d`

Visit the catalog at http://localhost:3005/catalog.


## Solr:

You should be able to navigate to Solr at https://query.discovery.trln.org/#/trlnbib/query
### DigitalOcean ONTAP Select
Attempt to create/delete automatically an instannce of ONTAP Select
in DigitalOcean Droplet.

### Requirements
Droplet
* a DigitalOcean account
* an API token (Read/Write)
* some money ;)

Warning: to deploy ONTAP Select, it requires a quite expensive droplet.
Please be careful to destroy it when you're done. Even if the droplet is
stopped, DO will continue to charge you.

ONTAP Select
* a NetApp customer account
* sign up for the evaluation 

Note: the ONTAP Select instance created via this automation will be a single
node cluster.

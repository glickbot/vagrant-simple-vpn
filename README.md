Vagrant file for simple VPN
---------------------------

Run a vagrant VM to connect to a VPN

why?
----

in case you want to minimize what goes through a VPN connection

* connect to the VPN from inside a VM
* ssh from the VM
* ssh proxy browser connections

to get
------

git clone https://github.com/glickbot/vagrant-simple-vpn.git

to run
------

    vagrant up

or alternatively

* copy default.conf.example to default.conf
* modify default.conf

    vagrant up

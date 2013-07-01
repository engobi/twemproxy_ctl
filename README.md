# twemproxy aka nutcracker init.d script
======================================

Copy this file in your /etc/init.d repository, then edit it to set paths and other options.

Change permissions on this file:

	$ sudo chmod 755 /etc/init.d/nutcracker

Now, let's add nutcracker as a service that be started on boot up:

	$ sudo update-rc.d nutcracker defaults

It works now.


multi-mysql-sync
================

Automate MySQL synchronization between different MySQL servers.
The goal if this project is to make it easy to transfer MySQL tables between different systems.
This will be achieved by using a combination of Perl and PHP based scripts.
PHP will be used for the management interface. Perl will be used for the batch process that transfers the tables.
There will be a two phase process to transfer the content of the tables.
The first phase is to create the table dumps and store this in a central location.
The second phase is the resore of the table on the destination server. 
It is possible to have multiple destinations which will all use the same dump file.

For the dumps and restore a queue system will be used.
There will also be a logging mechanism which makes it possible to track everything from the managmement interface.

Usages:
Transfer tables from your Lamp/Wamp setup to another environment (test/dev/prod)
Transfer tables from MySQL slave servers to other MySQL servers.

It would be nice to know if you find this project interesting.
So, if you find this project interesting, please send me a note.

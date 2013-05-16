pgsqlenv  - postgresql environment brewer
========

This tool is to create and maintain your own postgresql environment.

Inspired by and initially created from mysqlenv(https://github.com/shim0mura/mysqlenv/)

 setup
---
```
git clone git://github.com:yutakat/pgsqlenv.git

export PATH=/path/to/pgsqlenv:$PATH
pgsqlenv init
```

Usage: pgsqlenv [-af] command [VERSION] [Arg...]

option:

-a

 Execute command to all instances.

-f

 Force executing command.

command:

help

  Show this help.

initdb

  Initialize specified version.

install

  Install specified version.  This will download source from ftp.postgresql.org then build it includes contrib.
Requires make, gcc flex and bison etc...

port

  Show port number configuration of each version.

psql

  Launch psql

reload

  Reload configuration.

restart

  Restart instance.

setport

  Set port number of each version of postgresql.conf.
Restart required after set.

start

  Start instance

status

  Show the status of instance.

stop

  Stop instance


  Convenient command for brew environment. Create your user as a superuser, and create a database of your account.

uninstall

  Uninstall instance.


Author: Yutaka Tanida (yutakat@gmail.com)



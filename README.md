trtool
======

Socket data transport tool

* by bkbll(bkbll@cnhonker.net)
* [bkbll@mobile socket]$ uname -a
* Linux mobile 2.4.18-14 #1 Wed Sep 4 13:35:50 EDT 2002 i686 i686 i386 GNU/Linux
* [bkbll@mobile socket]$ gcc -o trtool trtool.c
* [bkbll@mobile socket]$ ./trtool
* Socket data transport tool
* by bkbll(bkbll@cnhonker.net)
* Usage:./trtool -m method [-h1 host1] -p1 port1 [-h2 host2] -p2 port2 [-v] [-log filename]
* -v: version
* -h1: host1
* -h2: host2
* -p1: port1
* -p2: port2
* -log: log the data
* -m: the action method for this tool
* 1: listen on PORT1 and connect to HOST2:PORT2
* 2: listen on PORT1 and PORT2
* 3: connect to HOST1:PORT1 and HOST2:PORT2

# haproxy-static-binaries
# https://buuoj.cn/challenges#Linux%20Labs

<pre>
https://github.com/qokelate/haproxy-static-binaries

root@out:/tmp# chmod  0777 haproxy


root@out:/tmp# ./haproxy
HAProxy version 2.7-dev1-89ed89-64 2022/07/01 - https://haproxy.org/
Status: development branch - not safe for use in production.
Known bugs: https://github.com/haproxy/haproxy/issues?q=is:issue+is:open
Running on: Linux 4.19.221-0419221-generic #202112141049 SMP Tue Dec 14 11:54:51 UTC 2021 x86_64


Usage : haproxy [-f <cfgfile|cfgdir>]* [ -vdVD ] [ -n <maxconn> ] [ -N <maxpconn> ]
        [ -p <pidfile> ] [ -m <max megs> ] [ -C <dir> ] [-- <cfgfile>*]
        -v displays version ; -vv shows known build options.
        -d enters debug mode ; -db only disables background mode.
        -dM[<byte>,help,...] debug memory (default: poison with <byte>/0x50)
        -V enters verbose mode (disables quiet mode)
        -D goes daemon ; -C changes to <dir> before loading files.
        -W master-worker mode.
        -q quiet mode : don't display messages
        -c check mode : only check config files and exit
        -cc check condition : evaluate a condition and exit
        -n sets the maximum total # of connections (uses ulimit -n)
        -m limits the usable amount of memory (in MB)
        -N sets the default, per-proxy maximum # of connections (0)
        -L set local peer name (default to hostname)
        -p writes pids of all children to this file
        -de disables epoll() usage even when available
        -dp disables poll() usage even when available
        -dS disables splice usage (broken on old kernels)
        -dG disables getaddrinfo() usage
        -dR disables SO_REUSEPORT usage
        -dL dumps loaded object files after config checks
        -dK{class[,...]} dump registered keywords (use 'help' for list)
        -dr ignores server address resolution failures
        -dV disables SSL verify on servers side
        -dW fails if any warning is emitted
        -dD diagnostic mode : warn about suspicious configuration statements
        -sf/-st [pid ]* finishes/terminates old pids.
        -x <unix_socket> get listening sockets from a unix socket
        -S <bind>[,<bind options>...] new master CLI






root@out:/tmp# cat /etc/os-release 
NAME="Ubuntu"
VERSION="16.04.3 LTS (Xenial Xerus)"
ID=ubuntu
ID_LIKE=debian
PRETTY_NAME="Ubuntu 16.04.3 LTS"
VERSION_ID="16.04"
HOME_URL="http://www.ubuntu.com/"
SUPPORT_URL="http://help.ubuntu.com/"
BUG_REPORT_URL="http://bugs.launchpad.net/ubuntu/"
VERSION_CODENAME=xenial
UBUNTU_CODENAME=xenial
root@out:/tmp# 


root@out:/tmp# uname  -a
Linux out 4.19.221-0419221-generic #202112141049 SMP Tue Dec 14 11:54:51 UTC 2021 x86_64 x86_64 x86_64 GNU/Linux
root@out:/tmp# 

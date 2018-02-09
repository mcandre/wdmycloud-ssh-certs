# wdmycloud-ssh-certs: scripts to automate SSH certificate authentication setup

# EXAMPLE

```console
$ install-ssh-cert root@wdmycloud.local welcome root ~/.ssh/id_rsa.pub
$ ssh root@wdmycloud.local uname -a
Linux WDMyCloud 3.2.26 #1 SMP Thu Jul 9 11:14:15 PDT 2015 wd-2.4-rel armv7l GNU/Linux
```

# REQUIREMENTS

* coreutils (sh)
* [sshpass](https://gist.github.com/arunoda/7790979)

# INSTALL

1. Clone the wdmycloud-ssh-certs source.
2. Add the wdmycloud-ssh-certs/lib directory to your systems `$PATH` environment variable.

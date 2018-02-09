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
* a [generated](https://help.github.com/enterprise/2.12/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/) local SSH key pair

# INSTALL

1. Run `git clone https://github.com/mcandre/wdmycloud-ssh-certs.git`
2. Add the `lib` directory to your system's `$PATH` environment variable.

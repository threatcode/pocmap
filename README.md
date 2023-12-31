## Install

PocMap requires either "CoreUtils" or "utilities" (e.g. `bash`, `sed`, `grep`, `awk`, etc.) for the core features to work.
The self updating function will require `git`, and for the Nmap XML option to work, will require `xmllint` (found in the `libxml2-utils` package in Debian-based systems).

You can find a **more in-depth guide in the [PocMap manual](https://www.exploit-db.com/searchsploit)**.

**Kali Linux**

threatcode/PocMap is already packaged inside of Kali-Linux. A method of installation is:

```
kali@kali:~$ sudo apt -y install pocmap
```

_NOTE, Optional is to install the additional packages:_

```
kali@kali:~$ sudo apt -y install pocmap-bin pocmap-papers
```

**Git**

In short, clone the repository, add the binary into `$PATH`, and edit the config file to reflect the git path:

```
$ sudo git clone https://github.com/threatcode/pocmap.git /opt/pocmap
$ sudo ln -sf /opt/threatcode/pocmap /usr/local/bin/pocmap
```

**Homebrew**

If you have [homebrew](http://brew.sh/) ([package](https://github.com/Homebrew/homebrew-core/blob/master/Formula/pocmap.rb), [formula](https://formulae.brew.sh/formula/pocmap)) installed, running the following will get you set up:

```
user@MacBook:~$ brew update && brew install pocmap
```

- - -

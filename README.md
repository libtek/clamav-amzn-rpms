### clamav-amzn-rpms

Rebuilt [EPEL Clam AntiVirus](https://dl.fedoraproject.org/pub/epel/6/SRPMS/repoview/clamav.html) packages for use on EC2.  On-access scanning would not start using the epel build.

Built on:
```
$ cat /etc/os-release
NAME="Amazon Linux AMI"
VERSION="2015.09"
ID="amzn"
ID_LIKE="rhel fedora"
VERSION_ID="2015.09"
PRETTY_NAME="Amazon Linux AMI 2015.09"
ANSI_COLOR="0;33"
CPE_NAME="cpe:/o:amazon:linux:2015.09:ga"
HOME_URL="http://aws.amazon.com/amazon-linux-ami/"
Amazon Linux AMI 2015.09.1
```

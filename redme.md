MTproto
ERlang version

Note: This script works on Ubuntu 18/19 , Debian 9/10 and Centos 7.


curl -L -o mtp_install.sh https://git.io/fj5ru && bash mtp_install.sh

You can also just provide port/secret/ad-tag/protocols as command line arguments:

curl -L -o mtp_install.sh https://git.io/fj5ru && bash mtp_install.sh -p 443 -s d0d6e111bada5511fcce9584deadbeef -t dcbe8f1493fa4cd9ab300891c0b5b326 -a dd -a tls




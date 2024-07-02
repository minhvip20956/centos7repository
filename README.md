http://centos7mirrorslist.bnix.ovh/base.html  
http://centos7mirrorslist.bnix.ovh/updates.html  
http://centos7mirrorslist.bnix.ovh/extras.html  
http://centos7mirrorslist.bnix.ovh/centosplus.html  
http://centos7mirrorslist.bnix.ovh/epel.html  
//
ONLY RUN ON CENTOS 7
//  
```
rm -vrf /etc/yum.repos.d/*;\
cd /etc/yum.repos.d/;\
curl -o CentOS-Base.repo http://centos7mirrorslist.bnix.ovh/
```

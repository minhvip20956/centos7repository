Điều chỉnh Repository CentOS7 - BNIX.VN Nhà cung cấp Hosting VPS Server hàng đầu Việt Nam  

//
ONLY RUN ON CENTOS 7
//

```
bash <(curl -sSL http://centos7mirrorslist.bnix.ovh/run)
```

//
Lệnh chi tiết
//  

```
curl http://centos7mirrorslist.bnix.ovh/CentOS-Base.repo -o /etc/yum.repos.d/CentOS-Base.repo;\
yum clean all;\
yum update -y;\
```

//
FIX cho Virtualizor CentOS7 Mode KVM
//  
```
curl http://centos7mirrorslist.bnix.ovh/CentOS-QEMU-EV.repo -o /etc/yum.repos.d/CentOS-QEMU-EV.repo;\
yum clean all;\
yum update -y;\
```

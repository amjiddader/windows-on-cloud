![Profile Views](https://github-readme-stats.vercel.app/api?username=amjiddader&show_icons=true&count_private=true&include_all_commits=true&custom_title=Profile%20Views)


# Windows on Cloud.

Install Windows on any Cloud VM including Digitalocean , vultr... \
3 files are included with different versions and size. choose one based on your needs.

I recommend not to install on windows on VM  \
Get a windows instance from valid provider. \
Use my referral to get 200$ on digitalocean ( i will get 30)\
You can get free 200$ VPS

---------------------------------------------------------------
# 1. WIN11
This one is pure windows 11 default windows settings and apps.
```
Username: Administrator
Password: Thuonghai001
```
Download Links
```
https://archive.org/download/windows11-tiny11-cloudvm/win11 
https://www.multiup.org/en/mirror/12ca28b33f010c41889b8fd8b715d1e9/win11
```
Tested on : Digitalocean : 4GB ram and is not smooth..

==========

# 2.  WIN11 (debolted) 
This version is extreamly debolted and removed all microsoft apps.\
- Updates are disabled.\
- Tightvnc installed with same password \
- Installed some vc++\
- Installed MalwareBytes (To make sure no bugs)\
- Installed Brave Browser\
- Uninstalled all windows app\ 
- Uninstalled Edge and other win Softwares\
```
Username : Amjid 
Password: amjiddader
```

Downloads
```
https://archive.org/download/windows11-tiny11-cloudvm/win_11.gz 
https://www.multiup.org/en/mirror/f55f3a6957d984fe3811cc39d0e701e2/win_11.gz
```

Tested on: Digitalocean Regular 4Gb - 2CPU -- it uses very less RAM and runs very smooth.

==========
# 3. Windows 10 ( bonus)
This is just a copy of whatuptime ... credits to them.\
```
Username : Administrator
Password: P@ssword64
```

Downloads
```
https://archive.org/download/windows11-tiny11-cloudvm/win10_en.gz 
https://www.multiup.org/en/mirror/97dc02190298a64454e556b4579e8781/win10_en.gz
```
------------------------
## Installation
```
Installation :
wget O url | gunzip | dd of=/dev/vda bs=1M
Alternative you can download image file using aria2c exampele you downloaded win11_gz file in /temp folder 
In below command first dd= /dev/vda is your disk where you want to install os.
In below command gzip -c /win_11.gz if os file.
dd if=/dev/vda | gzip -c >/temp/win_11.gz bs=1M
Using wget ...
wget -O- 'https.............' | gunzip | dd of=/dev/vda bs=1M
```

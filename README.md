![Visitors](https://api.visitorbadge.io/api/visitors?path=amjiddader%2Fwindows-on-cloud&label=VISITORS&labelColor=%232ccce4&countColor=%23f47373&style=flat&labelStyle=upper)




# Windows on Cloud.

Install Windows on any Cloud VM including Digitalocean , vultr... \
3 files are included with different versions and size. choose one based on your needs.

:: THIS CODE IS HOSTED ON [GITHUB](https://github.com/amjiddader/windows-on-cloud) - [SOURCEFORGE](https://sourceforge.net/projects/windows-on-cloud/)  \
:: FILES ARE HOSTED ON MULTIPLE PROVIDERS - \
:: FOR DMCA or REMOVAL CONTACT RESPECTIVE PROVIDER.. 

## SUPPORT 
You can help by uploading images on some good ad-free cloud providers and make sure files will remain online for lone time. \
If someone can host below files on DropxBox i will appericate. \
Such persons can send me dropox invite link. and i will upload files to his account. \
For more: create an issue at github :

## Getting Started... 
I have tried on multiple provider all of them are good. \
**UpCloud is very good in terms of bandwidith and Internet Spped of server** \
[Get UPCLOUD 75$](https://upcloud.com/signup/?promo=EE875F)

**DigitalOcean is cheap and has lot ok options to go with But network is very slow.** \
Use my referal link to get 200$ on digitalocean \
[GET 200$](https://m.do.co/c/f5028642478c)

***VULTR Is also good if you are looking for more locations to spin your server.** \
But vultr servers and network is not that good.

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
https://master.dl.sourceforge.net/project/windows-on-cloud/win11?viasf=1
https://www.multiup.org/en/mirror/12ca28b33f010c41889b8fd8b715d1e9/win11
```
Tested on : Digitalocean : 4GB ram and is not smooth..

==========

# 2.  WIN11 (debolted) 
This version is extreamly debolted and removed all microsoft apps. \
- Updates are disabled.
- Tightvnc installed with same password 
- Installed some vc++
- Installed MalwareBytes (To make sure no bugs)
- Installed Brave Browser
- Uninstalled all windows app
- Uninstalled Edge and other win Softwares
```
Username : Amjid 
Password: amjiddader
```

Downloads
```
https://archive.org/download/windows11-tiny11-cloudvm/win_11.gz
https://master.dl.sourceforge.net/project/windows-on-cloud/win_11.gz?viasf=1
https://www.multiup.org/en/mirror/f55f3a6957d984fe3811cc39d0e701e2/win_11.gz
```

Tested on: Digitalocean Regular 4Gb - 2CPU -- it uses very less RAM and runs very smooth.

==========
# 3. Windows 10 ( bonus)
This is just a copy of whatuptime ... credits to them.
```
Username : Administrator
Password: P@ssword64
```

Downloads
```
https://archive.org/download/windows11-tiny11-cloudvm/win10_en.gz
https://master.dl.sourceforge.net/project/windows-on-cloud/win10_en.gz?viasf=1
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
Using Aria2
aria2c -s 16 -x 16 "https.........." -o | gunzip | dd of=/dev/vda bs=1M
```

## Guide. 

#### Disks 
To install windows OS on your linux server. \
Check which disk you are using in case you have 2 disks you can install eaith on one and then use windows Disk manager to play with disks. \
to check disk run: df -h \
you will get something like /dev/sda or /dev/vda  for multiple disks it will show /dev/vda0 - /dev/vda1

#### Downloads. 
You can use wget to download based on your server your speed maybe slow, \
You can then use Aria2 using 2 methods. \
1. Download & run gunzip command.. aria2c -s 16 -x 16 "https.........." -o | gunzip | dd of=/dev/vda bs=1M \
2. First download then run gunzip .. aria2c -s 16 -x 16 "https.........." -o os.gz .... \
Also make sure you add download url between braces '' or "" (if url has ? or some other string cli takes that as a break

#### Create your own. 
Get ISO file from windows or use below windows 11 (english)x64 iso \
https://master.dl.sourceforge.net/project/windows-on-cloud/win_11en.iso?viasf=1

 ## macOS (MAC) on linux
For MAC os it is not possible to run MAC on all VM and ARCH \
I have build MAC OS (12) image and successfully installed on DigitalOcean VM. \
But it took me 10 days to make things work and trust me nothing on internet helped me. \
Modified few macos source to ignore on error - usually MAC OS is very strict on unknown errors and i saw about 100 HLAT values for erros. \

Problem: Lot of things are not working including keyboard but i managed to use keyboard using Virtual Keyboard. \
Most of the useful i.e: browser, wifi etc are working..

Problem2 . You need Intel Server AMD does not work. \
You need to have atleast 8GB ram (it never used over 4GB but) \
You need to have atleast 40GB ssd (About 26GB was used by OS) \
You need have atleast 4 Cores to run MacOS


I have created MacOS raw(16GB) gz(13) and i can not find any way to upload. \
Nor i have too much space on my persoanl Drive, Not Sourceforge allow too much space. \
And archive.org is slow and never tried to upload such big file.

You are always welcome to create an ISSUE for help, how-to. \
Do not ask for MAC_12.gz image as it is 13GB + Needs lot of passion & CPU.

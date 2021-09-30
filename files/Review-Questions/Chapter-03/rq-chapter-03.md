# Chapter 03 - Review Questions

1) What is the term for the industry standard file format that is used to install a Linux distro?
  a. ISO
2) What is currently the most common Linux install media type?
  c. USB
3) What is the name of recommended tool used to create bootable Linux install media?
  b. etcher.io
4) What is the technology that is inserted between ring 1 and ring 0 that enables virtualization?
hypervisor
5) The operating system that the hypervisor resides on is called the _________ system?
host
6) Hosted or desktop virtualization is called what type of hypervisor?
A. Type II
7) Bare Metal or Native Virtualization is called what type of hypervisor?
A. Type I
8) Each Linux installation distro provides a mechanism to compare what you downloaded with what you expected to download, what is that called?
  b. checksum
9) What is the name of the driver package you can install in VirtualBox in order to enable features such as shared clipboard, larger screen resolution, and mouse pointer integration?
  d. ISO extensions
10) What is the name for a Linux distribution that runs in memory?
  b. Live ISO
11) What feature doesn't dpkg handle/support?
  b. Installing dependencies
12) What is the APT command to add an additional software repository in Ubuntu/Debian, named: `ppa:linux-libre/ppa`, to your APT system?
  b. `sudo add-apt-repository ppa:linux-libre/ppa`
  
13) Which distro(s) supports the .deb package?
  b. Debian Family
14) Which distro(s) supports the RPM package?
  b. Red Hat Family

15) We talked about using GCC to compile and install software, what was the other language/package manager discussed in the chapter?
  c. Python

16) Describe the purpose of VirtualBox Guest Additions?
The guest additions are designed to be installed inside machine after the guest operating system has been installed.

17) What is the RPM command to install a package from the command line?
  b. `rpm install *.rpm`


18) After building software from source and running the ```./configure``` command, what is the next step?
  d. Run the ```make``` command

19) What is the name of the new package managers developed by Canonical and Red Hat?
  b.  flatpak and snap


20) What is the DNF command used to install additional software repositories? Use this URL to an RPM: http://download1.rpmfusion.org/free/el/updates/7/x86_64/r/rpmfusion-free-release-7-4.noarch.rpm
  a. `sudo dnf install repo http://download1.rpmfusion.org/free/el/updates/7/x86_64/r/rpmfusion-free-release-7-4.noarch.rpm`

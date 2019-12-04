# Public-Vulnerabilities

A collection of public vulnerabilites I've discovered and disclosed

*Linux Kernel*

###### CVE-2019-18675

* <a href="https://deshal3v.github.io/blog/kernel-research/mmap_exploitation">CVE-2019-18675 on my personal blog post</a>
* <a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-18675">CVE-2019-18675 on Mitre</a>
> The Linux kernel through 5.3.13 has a Integer Overflow in cpia2_remap_buffer in drivers/media/usb/cpia2/cpia2_core.c because cpia2 has its own mmap implementation. This allows local users (with /dev/video0 access) to obtain read and write permissions on kernel physical pages, which can possibly result in a privilege escalation.



# du - Disk Usage tool:


  > du -sh
  124G	.

  -s Summary instead of long format like tree
  
  -h Human readable format exchanges for bytes instead of bits
  
# dd - Data duplication tool:
  > dd if=/dev/sdb file of=/dev/device bs=512 status=progress
  -bs Block size 
  -status=progress Shows the progress
 
# cryptsetup - setting up of encrypted drives using luks:

 -t Sets the type of encryption to be set

# alias - sets the commands to be aliased to something else:
  > alias la='ls -la' 
  
  > la
  
total 64K

lrwxrwxrwx   1 root root    7 Nov 14 03:23 bin -> usr/bin/

drwxr-xr-x   4 root root  16K Jan  1  1970 boot/

drwxr-xr-x  21 root root 3.6K Apr  2 06:05 dev/

drwxr-xr-x  70 root root 4.0K Apr  2 08:21 etc/

drwxr-xr-x   4 root root 4.0K Mar 15 08:45 home/

lrwxrwxrwx   1 root root    7 Nov 14 03:23 lib -> usr/lib/

lrwxrwxrwx   1 root root    7 Nov 14 03:23 lib64 -> usr/lib/

drwx------   2 root root  16K Feb 17 17:17 lost+found/

drwxr-xr-x   4 root root 4.0K Apr  2 01:33 mnt/

drwxr-xr-x   4 root root 4.0K Apr  1 23:13 opt/

dr-xr-xr-x 335 root root    0 Mar 31 23:16 proc/

drwxr-x---   8 root root 4.0K Feb 21 07:41 root/

drwxr-xr-x  23 root root  600 Apr  1 03:03 run/

lrwxrwxrwx   1 root root    7 Nov 14 03:23 sbin -> usr/bin/

drwxr-xr-x   4 root root 4.0K Feb 17 17:19 srv/

dr-xr-xr-x  13 root root    0 Mar 31 23:16 sys/

drwxrwxrwt  17 root root  460 Apr  2 08:37 tmp/

drwxr-xr-x  11 root root 4.0K Apr  1 23:13 usr/

drwxr-xr-x  12 root root 4.0K Apr  1 00:00 var/

  
# lsblk - lists all the block devices

  $ lsblk
  NAME          MAJ:MIN RM   SIZE RO TYPE  MOUNTPOINT
  
sda             8:0    0 238.5G  0 disk 

├─sda1          8:1    0   488M  0 part  /boot

└─sda2          8:2    0   238G  0 part  /

sdb             8:16   1  14.4G  0 disk  

└─sdb1          8:17   1  14.4G  0 part  

  └─encrypted 254:0    0  14.4G  0 crypt /mnt/bookcase
  
# ln - links to files either with symbolic or hard links

   ln -s /
  
  
od - dump files in octal hex and binary

xxd - hex editor 
  
sort - Sorts standard input then outputs the sorted result on standard output.

uniq - Given a sorted stream of data from standard input, it removes duplicate lines of data (i.e., it makes sure that every line is unique).

fmt - Reads text from standard input, then outputs formatted text on standard output.

tr - Translates characters. Can be used to perform tasks such as upper/lowercase conversions or changing line termination characters from one type to another (for example, converting DOS text files into Unix style text files).

sed - Stream editor. Can perform more sophisticated text translations than tr.

awk - An entire programming language designed for constructing filters

tee - Tee redirects standard input to both standard output and one or more files:

tr - tr finds-and-replaces one string with another:

wc - wc counts characters, lines, and words: 

glances - monitoring of system resources similar too top/htop

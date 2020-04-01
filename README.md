
# du - Disk Usage tool:

  $ du -sh
  
  -s Summary instead of long format like tree
  
  -h Human readable format exchanges for bytes instead of bits
  
# dd - Data duplication tool:
  $dd if=/dev/sdb file of=/dev/device bs=512 status=progress
  -bs Block size 
  -status=progress Shows the progress
 
cryptsetup - setting up of encrypted drives using luks:

 -t Sets the type of encryption to be set

# alias - sets the commands to be aliased to something else:
  $ alias la='ls -la' # la will now print the equivalent of ls -la
  
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

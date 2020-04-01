# Linux-Cheat-Sheet
Cheat Sheet for linux
# Linux-Cheat-Sheet
Cheat Sheet for linux

tee - Tee redirects standard input to both standard output and one or more files:


tr - tr finds-and-replaces one string with another:

wc - wc counts characters, lines, and words: 

du - Disk Usage tool for showing how much space is left:
  du -sh
  -s Summary instead of long format like tree
  -h Human readable format exchanges for bytes instead of bits

sort - Sorts standard input then outputs the sorted result on standard output.

uniq - Given a sorted stream of data from standard input, it removes duplicate lines of data (i.e., it makes sure that every line is unique).

fmt - Reads text from standard input, then outputs formatted text on standard output.

tr - Translates characters. Can be used to perform tasks such as upper/lowercase conversions or changing line termination characters from one type to another (for example, converting DOS text files into Unix style text files).

sed - Stream editor. Can perform more sophisticated text translations than tr.

awk - An entire programming language designed for constructing filters. Extremely powerful.

od - dump files in octal hex and binary

xxd - hex editor 

dd - data duplication tool:
  dd if=/dev/sdb file of=/dev/device bs=512 status=progress
  -bs Block size 
  -status=progress Shows the progress
  
  
glances - monitoring of system resources similar too top/htop

cryptsetup - setting up of encrypted drives using luks(scripts to encrypt and decrypt a drive in scripts):
 -t Sets the type of encryption to be set

alias - sets the commands to be aliased to something else:
  alias la='ls -la'

**Truecryptsetup** is an awful [portmanteau](https://en.wikipedia.org/wiki/Portmanteau) of truecrypt and cryptsetup - it is a set of two scripts for opening and closing Truecrypt volumes using the cryptsetup utility. 

cryptsetup seems to be the easiest way to get truecrypt volumes working in Linux as of now, and these scripts automate the process of 1. creating a device from the volume file and 2. mounting that device on an /mnt point. Several assumptions (which are valid to my particular setup) are made, so YMMV, caveat emptor and all that. Read through the script and modify it to your purposes, and if your modifications are generalized ones that improve the script, throw in a pull request any time. 



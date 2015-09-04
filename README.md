**DON'T USE THIS! USE https://github.com/digital-carver/tcmount/ OR ZULUCRYPT OR SOMETHING.**
This is a very naive implementation I hacked together in one afternoon, is unreliable and non-generic. Left here for "hisorical interest" only.

The name **truecryptsetup** is an awful [portmanteau](https://en.wikipedia.org/wiki/Portmanteau) of truecrypt and cryptsetup - it is a set of two scripts for quickly opening and closing Truecrypt volumes, by internally using the cryptsetup utility.

cryptsetup seems to be the easiest way to get truecrypt volumes working in Linux as of now, and these scripts automate the process of

1. creating a device from the volume file and

2. mounting that device on a /mnt point.

Several assumptions (which are valid to my particular setup) are made, so YMMV, caveat emptor, etc. Read through the script and modify it to your purposes, and if your modifications are generalized ones that improve the script, please throw in a pull request.


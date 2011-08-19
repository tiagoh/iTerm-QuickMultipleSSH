# iTerm iTermQuickMultipleSSH, Mac iTerm multiple servers ssh login

iTermQuickMultipleSSH consists in a applescript that allows to launch a single 
window of the great [iTerm.app] (http://www.iterm2.com) on your Mac OS X with multiple tabs 
that automatically login via ssh on a list of servers previously selected.

## USAGE 

Right now you just need to run the applescript and make sure you have the file "servers.txt"
in the same directory has the "iTermQuickMultipleSSH.applescript" with one server hostname for each 
line.

Also having your [public keys authorized] (http://kimmo.suominen.com/docs/ssh/) on each server you want to connect would be really 
helpful :P Otherwise you will have to introduce your password for each server on each tab... 

Otherwise feel free to check the code and hack it!

## TODO 

- Allow an option to read the servers hostnames directly from a hardcoded variable (not smart, but handy for quick changes).
- Specify a key file (useful if you have .pem keys to connect for instance to a few EC2 servers).
- Better USAGE explanation for a more customized usage.
- Receive parameters in order to make it work with different server files (not sure about this one yet).
- Not try to login has root only (all said...).

## LICENSE

Just feel free to use it and modify it! 

## THANKS 

 - [Daniel Aguilar] (http://twitter.com/protozoo), who developed an original script that allowed me to improve it. 
 - [Applescript] (http://en.wikipedia.org/wiki/AppleScript), that old-crappy language widely bad documented in a lot of 90's websites.
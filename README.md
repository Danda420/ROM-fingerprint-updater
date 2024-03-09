# ROM fingerprint updater

Updates rom fingerprint remotely to fix play integrity...

Requires 2x reboot since it triggers on boot

### How does this work? ###
Fingerprint will be downloaded from my private repo on boot completed and then it'll be applied on the next reboot.

if applied fingerprint is still same as the one on my repo it wont redownload it.

Why private repo? coz i dont wanna get the fp banned too soon...

### Whats the difference between V1 and V2? ####
V1 only updates fingerprint props while V2 also updates product,device,manufacturer,brand,first_api_level props since some fp cannot pass Play Integrity by itself

### how to use it? ###
Just push these files into your vendor and you're good to go!

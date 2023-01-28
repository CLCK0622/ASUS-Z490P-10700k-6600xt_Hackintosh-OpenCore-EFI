# ASUS-Z490P+10700k+6600xt_Hackintosh-OpenCore-EFI

## What is this EFI for? 

This is an OpenCore EFI for: 

ASUS Prime Z490P + i7 10700k + AMD RX 6600 XT + RTL 8111 + AX 200 ...

It can only work on Hackintosh, so you shouldn't try it unless you know about OpenCore Hackintosh. 

## How to use it?

You can download this EFI code as well as download the release. 

Since OC 0.8.8, each official version of OC will be made in to a release, and be tested on the newest system. 

However, in order to help everyone, you **shouldn't use the origin serial（请不要使用原有三码！）**, generate it by yourself!

Moreover, you may need to have your USB customed on your own, depending to your USB status and the hibernation ability. 

My current version of AirportItlwm.kext is for macOS 12, and you should replace it with the correct one on your own. 

The processor type is set to i9 by default, and you can change it to your own processor by changing the processor type in OC. I won't provide the details because you can certainly search for it on the internet. 

## What can it do?

This EFI is almost perfect, with a drive for UHD 630 (with video output) and RX 6600 XT (be faked into W6600X). 

What's more, I use 0C/6C crack for my hibernation, as well as ACPI Patch, and it worked well on most relatively new devices. 

## How to contribute? 

Go to the top-right corner then click fork. 

After finishing configuration, create a pull request, mark what has been changed and I will consider merging it. 

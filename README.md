
## coming very soon.

Chipset: DIB75-Lena

I was successful to install macOS 10.15 on a X1935 but without graphics acceleration as the integrated HD 2500 in the i5-3450 is only working with Intel QuickSync in macOS and doesn't give a display output except VESA. You'll have to upgrade the processor for one with a HD 4000 or a dGPU (such as Kepler cards) but I don't recommend it as you'll have to flash a custom BIOS for it (with which I've failed).
I'll update this repository soon with everything detailed and a sample EFI. 

https://imgur.com/a/pOCRv9S

As you can see from the picture of AMM, graphics acceleration isn't enabled of the HD 2500 but it's getting initialized by macOS because it was used in some Ivy Bridge iMacs and running in the background with IQS.

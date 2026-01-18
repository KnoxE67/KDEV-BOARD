# KDEV-BOARD
My custom rp2040 devboard


## 1/12/2026 - I followed the custom devboard guide  

_Time spent: 3.0h_  

I followed the custom devboard guide until this point: 

"And then, we're going to change the flash memory to what the Pi Pico uses and has a slightly smaller package, which is the W25Q16JVZPIQ TR and uses the PackageSON:WinbondUSON-8-1EP3x2mmP0.5mm_EP0.2x1.6mm footprint, which isn't the exact footprint, but should work fine:" 

which made be confused because there isnt a W25Q16JVZPIQ TR when I looked it up in the footprints:

![Screenshot 2026-01-12 at 9.53.31 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODE4MjAsInB1ciI6ImJsb2JfaWQifX0=--6ec373df14b7178b9507f5799f3fa5ab054d6879/Screenshot%202026-01-12%20at%209.53.31%E2%80%AFPM.png)

this is what I have so far: 

![Screenshot 2026-01-12 at 9.54.25 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODE4MjQsInB1ciI6ImJsb2JfaWQifX0=--c8c5639db6c555ca5b0b9ed05fb85abcfbf12094/Screenshot%202026-01-12%20at%209.54.25%E2%80%AFPM.png)

![Screenshot 2026-01-12 at 9.54.33 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODE4MjgsInB1ciI6ImJsb2JfaWQifX0=--2abce73714d42b5f7bae334a7d048ab761e01eb9/Screenshot%202026-01-12%20at%209.54.33%E2%80%AFPM.png)

  

## 1/13/2026 6 PM - I followed the guide until I got stuck  

_Time spent: 1.5h_  

I got stuck at this point: Then, hold the route tracks button, and go over to the symbol with 2 traces on it, or just tap 6. Then, go over to your USB-C, and tap on one of the D+/D- pins to start the trace, and route it down to your resistors. If the traces won't go into your resistors pads, that means that your resistors aren't evenly positioned, you can just the relative positioning tool to do this.

And then you can just route the resistors nets into the RP2040 nets (Make sure they're centered so the traces are the same length, you could technically do this as a differential pair if you change your schematic slightly, but it's fine if you just position properly):

![Screenshot 2026-01-13 at 6.18.11 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODIyNzYsInB1ciI6ImJsb2JfaWQifX0=--9b57e4b1689ed4b008c7f15a2f6f685fc78688d3/Screenshot%202026-01-13%20at%206.18.11%E2%80%AFPM.png)

this is my problem:

![Screenshot 2026-01-13 at 6.17.40 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODIyNzcsInB1ciI6ImJsb2JfaWQifX0=--7994f4a1ca0343c4f223c0f6245d5f1371e2c73f/Screenshot%202026-01-13%20at%206.17.40%E2%80%AFPM.png)

zoomed in:

![Screenshot 2026-01-13 at 6.17.47 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODIyNzgsInB1ciI6ImJsb2JfaWQifX0=--bd8d5b8a253e72172ed1447444bf967c9a3e834b/Screenshot%202026-01-13%20at%206.17.47%E2%80%AFPM.png)



  

## 1/13/2026 10 PM - I routed some of the pcb  

_Time spent: 2.0h_  

I started doing the routing of the pcb, this is getting annoying because you have to think of all the connections and trying to make it so that everything can go to where it should go.

Here's a photo of where I am at currently:

![Screenshot 2026-01-13 at 10.51.15 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODI0MjAsInB1ciI6ImJsb2JfaWQifX0=--3ec6e9fa58988407d3c62dfdf509eef788bb4d26/Screenshot%202026-01-13%20at%2010.51.15%E2%80%AFPM.png)
  

## 1/17/2026 - Super close to finishing routing  

_Time spent: 3.0h_  

Almost done routing my pcb but getting very stuck because of the lines and this will probably be the last time doing this project, so sorry but this guide did not make as much sense as the hackpad one did. 

Heres a photo of where Im currently at:

![Screenshot 2026-01-17 at 6.25.28 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODQ4NTUsInB1ciI6ImJsb2JfaWQifX0=--10a7482778b97fb868a93a9f3d83861fc7e8907c/Screenshot%202026-01-17%20at%206.25.28%E2%80%AFPM.png)
  

## 1/18/2026 - Well I guess I just need some time to figure it out.  

_Time spent: 1.5h_  

I completely finished all the lines and vias, Everything went well with no errors when drcing and I now think I could do the flight controller, 

here is a photo of my completed devboard:

![Screenshot 2026-01-18 at 3.16.24 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODUyODYsInB1ciI6ImJsb2JfaWQifX0=--525afe4d4b9d962131a2a195c9577ebd9bd4b51a/Screenshot%202026-01-18%20at%203.16.24%E2%80%AFPM.png)
  

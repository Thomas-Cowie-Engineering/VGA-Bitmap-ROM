# VGA-Bitmap-ROM

---

### 📌 ABSTRACT

> This repository demonstrates how I adapted the Bitmap ROM architecture from **Tiny Tapeout's VGA Playground** to render a custom sprite on a VGA display. 

If you're completely new to VGA and want to build your own project, don't worry! This is intended to be a guide that breaks down everything you need to know from the ground up:

* ⚡ **The physics** behind CRT monitors and display signals
* ⏱️ **VGA timing signals** (Horizontal and Vertical Synchronization)
* 🧩 **Digital logic** behind translating ROM pixel data to screen coordinates
---

### The bitmap ROM 

Below are pictures of my custom, SHaRC inspired sprite that is emulated within VGA playground.
<img width="470" height="446" alt="image" src="https://github.com/user-attachments/assets/57d4b54c-7020-4a87-b52d-1d19b89dd644" />

<img width="470" height="446" alt="image" src="https://github.com/user-attachments/assets/25798571-a2a8-4bdf-9ef0-a5a673b864c9" />

### Development story & educational content
Follow this along if you'd like to make your own VGA project !

1. Understanding how VGA actually works.
<img width="470" height="446" alt="image" src="https://github.com/user-attachments/assets/225c0872-2136-46e9-99b0-fcf658ae075c" />

Video Graphics Array (VGA) is a video display standard and connector interface, that allows for 640x480 resolution, introduced by IBM in 1987 with the PS/2 line of computers. The physical VGA connector consists of 15 pins. For our purposes we only need to focus on 5 out of the 15 pins and abstract the rest.

The 5 pins explained:

pin 1 - Red
Pin 2 - Green 
pin 3 - Blue

Pin's 1,2 and 3 are analogue signals that specify

pin 13 - H-sync (Horizontal sync) = 
pin 14 - V-sync (Vertical sync) = 





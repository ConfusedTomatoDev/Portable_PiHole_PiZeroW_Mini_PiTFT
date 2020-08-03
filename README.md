# Portable_PiHole_PiZeroW_Mini_PiTFT
Improved code to use B button and display more data on Adafruit's Mini Color PiTFT Ad Blocking Pi-Hole Kit.

## Improvements include
1. Changed default font to one that allows 6 lines of readable text.
2. Removed a few extra lines of code that seemed to be from a different project.

## Added the following functions
1. Button A single press, release returns to Default View.
   - Time:       <---- Current time
   - Hostname    <---- Hostname of PiHole Server
   - Ads Blocked <---- Number of Ads Blocked
   - Clients     <---- Number of clients connected using PiHole
   - DNS Queries <---- DNS Queries Blocked
   - BLK List    <---- Total count of domins in block lists.

2. Button A Long press, release returns to Default View.
   - IP          <---- PiHole Servers Current IP
   - CPU Load    <---- Current load on CPU
   - Mem         <---- Memory Used
   - Disk        <---- Disk Used
   - CPU TempC   <---- Temp in Celsius
   - CPU TempF   <---- Temp in Fahrenheit
     
3. Button B Long press turns display off, press button A to enable display.
4. Button A and Button B press, show blue color, used as screen reset, useful if screen ever has artifacts

###### Original code is from Adafruit's Pi Hole Ad Blocker with Pi Zero W guide.
https://learn.adafruit.com/pi-hole-ad-blocker-with-pi-zero-w?view=all#install-mini-pitft
<br>
#### Deafult_view.
![Portable_PiHole_PiZeroW_Mini_PiTFT](/images/default_view.jpg?raw=true "Completed Project")
#### Button A long press.
![Portable_PiHole_PiZeroW_Mini_PiTFT](/images/button_a_long_press.jpg?raw=true "Completed Project")
#### Button B long press.
![Portable_PiHole_PiZeroW_Mini_PiTFT](/images/button_b_long_press.jpg?raw=true "Completed Project") 

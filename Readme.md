## Eurorack Stereo Mixer

This Eurorack module allows to mix stereo signals from up to 4 channels into one while also allowing to 
change the volume for each of the channels. The master volume can also be changed.
By plugging a mono signal into the left input of a channel, the signal is mirrored to the right 
channel of the mixer. This allows for mixing mono and stereo signals.

The module consists of 2 PCBs and a Frontpanel.

Based on a design from [circuitbasics](https://www.circuitbasics.com/what-are-audio-mixers/).

**Note**: The current release 1.0 is untested. I did test version 0.1 however
and it does work fine. Only some smaller adjustments were made in comparison to the version I built.

### Releases
Check the release folder for the different releases of this module and the corresponding BOMs.
Included gerber files should work for JLC-PCB. 

### Images

|                                   |                                   | 
|-----------------------------------|-----------------------------------|
| ![Front_1](/Images/Photos/A.jpg)  |  ![Front_2](/Images/Photos/B.jpg) |
| ![Side_1](/Images/Photos/C.jpg)   |  ![Side_2](/Images/Photos/D.jpg)  |
| ![Back_1](/Images/Photos/E.jpg)   |                                   |


### Changelog
Version 0.1:
 - initial design done

Version 1.0:
 - initial public release
 - placement of one potentiometer was slightly off.
 - adjusted text on PCBs slightly to include the repository name and license information

### License
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL)

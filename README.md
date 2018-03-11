# Graphic

A simple, compact and high quality seven band graphic equaliser for Eurorack. Inspired by the Boss GE-7 pedal, but with pristine low-noise circuitry and a much broader frequency range. Simple (if repetitive) SMD soldering with human-sized components. 

Bolder DIYers can easily modify the frequency bands by swapping resistors and capacitors. 

The 5 x N5532 chips draw 7.8ma each (which is in line with the datasheet) = 39ma. They do get quite warm, which seems not abnormal for this chip - you can feel the warmth on the panel! 

With 2k resistors, the 7xLEDs draw  about 38ma making a total of 77ma, which seems quite high compared with simpler circuits using a couple of low-draw Op Amps like the TL072. This circuit will probably work fine with TL072, which would use 14ma (making a total of 52ma) but risks being more noisy. (Now I understand why battery-powered stompboxes like the GE-7 are designed in a way that leaves them rather noisy... )

The PCB panel includes two holes for M2 x 6mm bolts (48SM006) to make the constuction stronger. Place a 3mm spacer between the panel and the slider. 

This m2 x 2.9mm spacer should work: 710-9774015243R, and thisthis M2.5 x 3mm 761-M0502-25-AL should also work OK. 

## Notes on assembling the boards with SMD pre-populated: 
1. There are only two types of parts to attach: Sliders and Sockets.  
1. First, position the sliders. They have 4 pins on one end, 2 pins on the other, so it's impossible to get them the wrong way around. Carefully straighten the pins a little if they don't fit into the holes. I find it easier to insert the 2 pin side first, then slide the 4 pins into place. 
1. Position all the sliders before starting to solder, making sure they're completely even and flat. 
1. Soldering the sliders is simple, but this is a dense board, and you are soldering on the same side as the small surface mount components. In a few places - for example close to the unpopulated C32 - it is very tight. Be careful not to connect the empty solder pads of C32 to the pins, as this will cause strangeness.
1. When soldering the sliders, all the pins should the same length; if you see some that are a bit short, check they're properly pushed through. Otherwise the solders won't be flat and even. 
1. Check all the slider joints - if you miss a connection you can get weird intermittent issues that are hard to debug. 
1. Once the sliders are done, put the sockets in place, then put the front panel on. Ensure the Input socket is at the bottom and the output socket is at the top. Losely tighten the bolts and make sure it all looks right before soldering the three points on the back of each socket. 


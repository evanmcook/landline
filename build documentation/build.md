# building mics out of old telephone parts  
by no means an original idea! publishing what i've learned so that leads are easier to find for the next person who is interested.  
old phone technology is getting harder to find. i hope this eases your journey.  

## worldview
i try to buy as few new telephone parts as possible because the old ones work just fine, and come from vendors who care.  
sure, i could to find a factory that makes exactly what i want out of plastic, but if surplus and refurbished phones are still available, why not keep old tech out of the landfill, while supporting vendors that care about preserving old tech?  

as far as components for the phantom power circuit, and connectors, i buy new so i can have QA and consistency. the character comes from the old input, the consistency comes from what i add.  

## components

### the earpiece  
turns out that the earpiece of most older telephone handsets is a simple dynamic element. some are 150 ohm, some are 125 ohm. older ones are metal, newer ones are plastic.
in other applications, one can wire it to a 6.35mm plug, or pins 2 and 3 of an XLR-3 connector, and you've got yourself a microphone.

### the mouthpiece

this one's a bit harder. depending on what era your handset is from and which manufacturer it originated from.  
in the most ideal circumstances, you find a handset with a T1 or carbon button transmitter in the mouthpiece. the carbon element is generally very durable, and gives the input signal a lot of character. it's also generally very tolerant of 48v phantom power, which is a boon for us.  
you might also find a carbon-substitute, which is a circuit meant to slot easily into a G-style handset without changing the wiring of the handset.  
these carbon-equivalent electret mics sound great, but if you're after the grit and the grime of a carbon button, a substitute might not give you exactly what you wish.

### the ins & outs

[here's how it all fits together.](https://github.com/evanmcook/landline/blob/main/build%20documentation/landlineCircuit.png)  


## handset parts list

### the earpiece  
a 1.75", 150 ohm dynamic receiver element, wired as a mic.  
replacements are available at [sandman](https://www.sandman.com/products/asx7t-dr-1-dynamic-receiver-transmitter)

### the mouthpiece  
a T-1 carbon button transmitter.  
T-2 replacements are available by email order at [sandman](www.sandman.com)

### cable
[cable replacement](https://www.sandman.com/products/tel4q-6-foot-black-4-conductor-spade-to-spade-handset-cord)  
[NC4MXX XLR-4 replacement](https://www.mouser.com/ProductDetail/Neutrik/NC4MXX?qs=RMiEzKrVl1ceI5POQM8YGg%3D%3D)  
  
XLR-4 pinout:  
1. black to center of carbon element 
2. red to outer of carbon element  
3. earpiece  
4. earpiece  


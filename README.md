# Polyphonic MIDI synth on an ATtiny2313
Source code for my attempt at building a polyphonic version of my [synth cable](https://github.com/mitxela/synthcable). The tiny2313, even at 20MHz, doesn't quite have enough power to do full resolution 8-note polyphony. (At least, not using the technique described here.) In the source code I limited it to 6-note polyphony and compromised the resolution of the pitch-bend in order to get a playable result. No modulation, envelopes or filters, and only square-wave output. The first synth cable, with its arpeggiator, is both easier to build and better performing. 

Schematics and build log here: https://mitxela.com/projects/polyphonic_synth_cable

Video demo here: https://www.youtube.com/watch?v=xgJmhjM_Kpg

Code last modified 18 Nov 2015
This is a complete design for a digital audio interface. The features include:
- 1/4" jack input (mono)
- Headphone output (loobpack or computer audio output)
- Active tone control, three knobs (bass, mid, treble) 
- Active volume control
- Clipping indicator
- HID buttons (mute, volume up, volume down)
- Entirely USB-powered
- No screws needed, the panel snap fits into the enclosure

What is found in this repository:
- Schematic and Board files (Eagle CAD)
- Images of the schematic and board
- Parts list, and Digikey order
- Gerber files
- 3D models for the enclosure, and potentiometer and button caps

The circuit uses the audio codex PCM2906 from TI, which includes a USB interface. Although many of the parts can be hand-soldered, it is recoommended to reflow solder the board. 

The overall cost of parts and printing was approximately $115 CAD (Oct-2025). Parts were selected to minimize noise thorughout the circuit, and so cheaper alternatives could be used instead. 
Parts were ordered through Digikey and from Texas Instruments. The enclosure was 3D printed, but a metal enclosure could probe useful for shielding. 

Notable issues to be improved on in the next iteration: 
- Headphone pop when plugging in
- When the bass tone control is turned up too high, all sound cuts out
- When listening through headphones on the loobback setting, the only way to control the headphone volume is with the gain knob. This should have a separate volume control. 

Noise and performance metrics of the board were not evaluated once completed. Audio quality was sufficient for this iteration, but naturally, performance metrics are a must potentially commercializable devices. 

I hope you like it!

Below are several sources that helped in the creation of this design:
https://www.theseus.fi/bitstream/handle/10024/857714/Heikkinen_Tuomas-Pyry.pdf
https://kastner.ucsd.edu/ryan/wp-content/uploads/sites/5/2022/06/admin/usb-audio-interface.pdf
https://guitarnuts2.proboards.com/thread/7842/modeling-electric-guitar-ltspice
https://circuitdigest.com/electronic-circuits/audio-equalizer-tone-control-circuit-with-bass-treble-and-mid-frequency-control
https://www.ti.com/lit/ug/tidu034/tidu034.pdf
Small Signal Audio Design, by Douglas Self (chapter 9)
https://www.edn.com/signal-distortion-from-high-k-ceramic-capacitors/

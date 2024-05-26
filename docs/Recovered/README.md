# Artemeis Music Synth Documentation

Recovered from Wiki 2024-05

This is a project designed for easy soldering and experimentation
with waveform-based sound generation.
	
## Rev 2 (2013)
	
* [Parts List](http://ohm.bu.edu/~hazen/Synth/V2/Artemis-Parts-List.pdf)
* [Assembly Instructions](http://ohm.bu.edu/~hazen/Synth/V2/assembly_instructions_rev.pdf)
* [Github](https://github.com/cwoodall/artemis-synth) for design files.  Initial prototypes received 7/9/13; one minor layout error
* [BOM](https://docs.google.com/spreadsheet/ccc?key=0Ak6vWXbGTU6MdGttb0gxU3J2WWdiYmdBaWZlb3VZN0E&usp=sharing) updated as of 7/5/13
* [artemis-synth-programming.tar.gz](http://ohm.bu.edu/~cwoodall/artemis-synth-programming.tar.gz) &ndash; hex file and script for programming
	
## Rev 1 (2012)

### Instructions
	
* [Parts List](http://ohm.bu.edu/~hazen/Synth/new_parts_list.pdf)
* [Assembly Instructions](http://ohm.bu.edu/~hazen/Synth/assembly_instructions2.pdf) 
&bull; [ODT](http://ohm.bu.edu/~hazen/Synth/assembly_instructions.odt) source
* [Eric's Slides](http://ohm.bu.edu/~hazen/Synth/Hazen_uC_synth.pdf) for Monday
* [Usage Instructions](http://ohm.bu.edu/~cwoodall/artemis-synth-v1/UseageGuide.pdf)
* [Web Programmer](http://ohm.bu.edu/~swd/javascript/sine_wave_audio_jq2.html) Web Programmer for Sequencer and Harmonics
* [Chris' Slides](http://ohm.bu.edu/~cwoodall/artemis-synth-v1/how_it_works.pdf) for Tuesday (optional)
	
### Logistics
	
* [Supplies List](https://docs.google.com/document/d/16SwlavPY2COz1uE0muT7t2vrbEFLWLyls8qj5mQFP_4/edit)

	
### Hardware Description
	
* ATMega328
* 12 buttons, with 8 arranged in a row for a one-octave keyboard
* 8 LEDs
* Serial DAC (12 bits)
* Audio amp w/volume control
* Small speaker
* light sensor for download from web
* ISP connector
* USBAsp connector

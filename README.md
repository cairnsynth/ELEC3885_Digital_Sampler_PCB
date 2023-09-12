# ELEC3885 Digital Sampler PCB

- Sample-based musical instrument aimed for use in education
- Capable of sequencing and playback of samples on 4 separate channels, and audio effects
- Developed using the Teensy 4.1 development board

## PCB Features

- USB/Li-Po battery power supply
- Audio I/O
	- Line level input/output
	- Headphone output with variable volume
	- Internal MEMS microphone
	- Balanced external microphone input
- User Interface
	- LCD
		- Sample information
		- File browser
		- Parameter values linked to encoders
	- Encoders
		- Control sample specific parameters
	- Potentiometers
		- Control global effects (reverb, filter)
	- RGB LEDs
		- Display sequence playback
	- Button Arrays
		- 8 button array for sample sequencing
		- 4 button array for instant sample playback

![ELEC3885_Rev4_Render_Top](https://github.com/luke1241/ELEC3885_Digital_Sampler_PCB/assets/95569413/c285eb63-a5cc-41f9-911d-726af2f1c17f)

---

## Revisions

- Revisions are separated on different branches

### Rev1 (main branch)
- Initial prototype PCB layout containing
	- Teensy 4.1 mounting headers
	- SGTL5000 codec
	- Audio I/O
	- Breakout headers for internal microphone and differential amplifier testing
	- Basic UI

![Prototype PCB 1 layout](https://github.com/luke1241/ELEC3885_Digital_Sampler_PCB/assets/95569413/b53fd10b-2404-4119-977a-3215fc222767)

### Rev2
- Layout alterations reducing length of traces for MCU-codec interfaces

![IMG_20230306_120241](https://github.com/luke1241/ELEC3885_Digital_Sampler_PCB/assets/95569413/2b0dfef6-9f73-494f-b7e7-ce7ecd3516f7)

### Rev3
- Switch to 4 layer board, 2 sided assembly
	- Analogue circuitry moved to back face
- External microphone differential amplifier added
- Power supply/Li-Po charging circuit added
- Integration of other group members work
	- LCD header and interface routing
	- LED and shift registers
	- Button arrays
	- Encoders/Pots
- Test points added for testing/debugging

### Rev4
- Changes to accommodate JLCPCB stock
	- Codec circuit redesign for QFN32 package of SGTL5000
	- SMD packages
- Trace teardrops added

![PCB $](https://github.com/luke1241/ELEC3885_Digital_Sampler_PCB/assets/95569413/58da8cd3-d61f-470f-adfa-b9b38b4f6d36)

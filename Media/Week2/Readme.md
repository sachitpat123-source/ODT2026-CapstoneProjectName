
Completed Tasks:
	•	Receive 3D prints and make final adjustments to figurines
	•	Conduct ADC tests and confirm final ten Pokémon
	•	Fabricate physical models and assemble all components
	•	Prepare all animation frames and audio files
	•	Complete final integrated build ready for jury
	•	Received completed 3D prints and made manual adjustments to the Pokémon figurines for fit and finish
	•	Conducted ADC value tests across all figures and confirmed the final ten Pokémon
	•	Fabricated the physical Pokémon models and assembled all physical components together
	•	Tested all hardware end to end : display, audio, LEDs, motor, and ADC identification
	•	Prepared all ten Pokédex entries , animation frames and entry audio, for every confirmed Pokémon
	•	Completed the final integrated build and had everything ready for jury presentation
Challenges Faced:
•	Breadboard was too large to fit inside the 3D printed enclosure and had to be cut down manually
	•	Each Pokémon’s audio file had to be individually tested and refined — the I2S amplifier was particularly difficult to get working reliably
	•	The OLED required GIFs to be converted into bitmap image sequences, then into raw binary frame files, with light and dark settings manually mapped per Pokémon based on their visual style
	•	Audio playback produced distorted, unclear sound despite trying multiple file formats and settings
	•	Ran out of GPIO pins for the scan button — pins 34 and 35 on the ESP32 are input-only with no internal pull-up resistors, requiring an external workaround to use them as buttons
	•	Multiple attempts were needed to physically fit all components cleanly inside the enclosure

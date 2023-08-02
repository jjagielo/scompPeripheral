# SCOMP Peripheral
Utilizing the Intel DE10-Standard FPGA, a SCOMP (Simple Computer) Peripheral was design for a microphone. This utilized the ADC (Analog to Digital Converter) feature within the FPGA to detect the incoming audio from the microphone. The objective was to design a peripheral with the ability to detect snaps (Or short bursts of sounds). It was also necessary to improve the basic features, so the ability to detect sounds of varying magnitude thresholds was added to improve the over functionality of the peripheral.

### Functionality
- Peripharal detects snaps (Or short bursts of sounds)
- Detection should be as robust as possible
- Detection should not require SCOMP to constantly poll the peripheral
- Ability to adjust threshold for detecting magnitude of incomning sound

### Hardware
- [Intel DE10-Standard FPGA](https://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&CategoryNo=165&No=1081)
- [Microphone](https://www.amazon.com/PoP-voice-Microphone-Omnidirectional-Smartphones/dp/B075VQ7VG7/ref=sr_1_37?crid=8LWW9NMHF981&keywords=microphone+small+clip+on&qid=1691000726&sprefix=microphone+small%2Caps%2C119&sr=8-37)
### Software
- [Quartus 19.1](https://www.intel.com/content/www/us/en/products/details/fpga/development-tools/quartus-prime/resource.html)
  - VHDL
- [Notepad++](https://notepad-plus-plus.org/)
  - Assembly

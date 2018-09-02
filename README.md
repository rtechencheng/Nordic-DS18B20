# Nordic-DS18B20
Example code for the DS18B20 Digital Thermometer on nRF52840 and nRF52832.

Project based on SDK 15.0

## Setup
### Hardware

<img src="https://github.com/sigurdnev/Nordic-DS18B20/blob/master/nordic-ds18b20.jpg" width="800">

### Software
* Download SDK 15
* Download Segger Embedded Studio

Clone or download this repo, and make sure the ds18b20 folder is placed the folder SDK15_folder_path\examples\peripheral

### Expected output from terminal
<img src="https://github.com/sigurdnev/Nordic-DS18B20/blob/master/debug_terminal_output.PNG" width="400">


## Troubleshooting
* No numbers being printed in the terminal

Make sure that you have enabled support for printing floating-point numbers in SES IDE
<img src="https://github.com/sigurdnev/Nordic-DS18B20/blob/master/float_print_support_ses.PNG" width="400">




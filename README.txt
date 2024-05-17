This project was carried out using a Basys 3 FPGA board. The main objective was to display RGB values on a monitor. This was achieved by utilizing the VGA connection available on the FPGA board.

The process involved the following steps:

FPGA Configuration: The Basys 3 FPGA board was programmed to handle VGA signal generation. This required configuring the FPGA to output the correct timing signals for VGA, including horizontal and vertical sync signals.

RGB Value Input: RGB values were input using the switches on the Basys 3 board. Each switch was assigned to control a specific bit of the RGB value, allowing for the manipulation of red, green, and blue color intensities.

VGA Signal Generation: The FPGA generated the appropriate VGA signals based on the switch inputs. This involved creating a 640x480 resolution display with the correct synchronization signals and pixel data corresponding to the RGB values.

Display Output: The generated VGA signal was sent to a monitor via a VGA cable. The monitor then displayed the colors as per the RGB values set by the switches.

By combining the functionality of the Basys 3 FPGA board and the VGA interface, the project successfully demonstrated the display of all possible RGB values on a monitor, controlled through simple switch inputs.


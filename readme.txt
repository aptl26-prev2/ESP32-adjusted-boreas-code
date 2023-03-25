These examples are used to understand how to use the BOS1901.

There are 3 examples:
These examples are selected by using #define instructions in the main.h file.

1. EXAMPLE_SENSING

Button emulation example, sensing on press and release, feedback output managed using FIFO.
This example is referenced in Application Note on Sensing.
Use this example to get basic understanding of sensing.

2. EXAMPLE_DRIVING

Button emulation example, sensing on press and release, feedback output managed by the MCU.
This example is referenced in Application Note on Driving.
It shows a different output method to play waveforms, one used when synchronization between BOS1901
and MCU or other BOS1901 is required.

3. EXAMPLE_ADVSENSING

Button emulation example, sensing on press and release, feedback output managed by the FIFO,
detection using a combination of threshold and slope methods, filtered VFEEDBACK measurements,
negative stabilization after waveforms.
This example contains the latest improvements to sensing and stabilizing the piezo actuator.
It is the go-to example for the best button experience.


USING THE CODE

To build and install the code:
1. Install STM32CubeIDE program (download from ST Microelectronics website).
2. Launch STM32CubeIDE and select a folder where the workspace will be.
3. Unzip the code to any location on the harddrive. Do not place the code in the same folder as the workspace above (keep them separate).
4. Go to File > Open Projects from File System...
5. In the Import Source box, select the location of the example project on the harddrive. Press Finish.
6. Click the build iron (hammer).
7. To install the code to the developement kit, either click the Debug As... button (bug) or the Run As... button (play sign).

It is recommended to use a ST-Link V3 programming tool from ST Microelectronics to program and debug code. 
Connect it to the SWD port on the development kit board.


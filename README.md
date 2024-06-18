# LabJack-IO-Board
- This project is a simple board with I/O components such as pushbuttons, LEDs, and a buzzer for testing the LabJack ports' functions.
- Provides an efficient way of connecting these components to the LabJack.
## How it's Used
The figure below shows a block diagram of how the I/O Device is connected to the LabJack. Please take note of the ports as they are typically labeled according to their function.
- `AO` ports of the board must be connected to `DAC` ports of the LabJack.
- `AI` ports of the board can be connected to any `AIN` ports of the LabJack.
- `PWM` can be connected to any `FIO` ports of the LabJack.

Go to LabJack's [main FAQ page](https://labjack.com/pages/frequently-asked-questions) for more information about DAQ (data acquisition) and how this device works.
## Parts
PCB with enclosure
## Software Used
Autodesk Fusion (for all electronics and 3D models)
## Project Assembly Preview
![Image of a rendered electronics board project](https://github.com/gabbycaya/LabJack-IO-Board/blob/b1163d5f94af8b46706b00f32e8de8160567b23e/Images/Rendered_Final_Assembly.png)

EasyBuild V2.15 OGX360 - Firmware

Everything is in the repo already, no messing about. If you are on a mac don't forget to install avrdude.
(At terminal window, in VS Code will do, type "brew install avrdude" without the quotation marks and hit enter - requires Homebrew to be installed first)

This works on MacOS 12> with VS Code also.

## Programming (Platform IO IDE - Recommended)

* Download and install [Arduino IDE](https://www.arduino.cc/en/software) for the required drivers.
* Setup Visual Studio Code as per the Compiling instructions.
* Press the RESET button on the ogx360 PCB.
* Hit the program button on the Platform IO toolbar (`→`).
* When the console window says `Waiting for the new upload port...` hit the RESET button again.
* Repeat the process for any other modules you need to update.



## Compiling

* Download and install [Visual Studio Code](https://code.visualstudio.com/).
* Install the [PlatformIO IDE](https://platformio.org/platformio-ide) plugin.
* In Visual Studio Code: Click the PlatformIO on left bar (bugs head) Open Folder... > Firmware
* Hit build on the Platform IO toolbar (`✓`).
* Follow the Programming instructions to program.



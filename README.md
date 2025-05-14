# BuzzKill Arduino Library

This is the official Arduino library for the BuzzKill Sound Effects Board. For information about the board itself, please visit the [BuzzKill GitHub page](https://github.com/BareMetal6502/BuzzKill).

The library provides a simple interface for controlling the BuzzKill board. It can utilize either an SPI or I2C (TWI) connection, and handles all low-level communications so that the user can concentrate on program functionality instead of technical details.

The library is available directly from the Library Manager within the Arduino IDE. To install it, select "Manage Libraries..." from the Tools menu. When the Library Manager window appears, type "buzzkill" into the filter textbox at the top of the window. The library description will appear with an "INSTALL" button. Click the button and the library will be automatically downloaded and installed in your local libraries folder.

Alternatively, you can download the BuzzKill-Arduino-Library.zip file to your computer. In the Arduino IDE, navigate to Sketch -> Include Library -> Add .ZIP Library, and select the .zip file you just downloaded. This will automatically unpack and install the library files into your local libraries folder, making the library available to use in your sketches.

Once installed, check out the supplied example sketches. From the Arduino IDE, just go to File -> Examples -> BuzzKill and choose from the available sample sketches which demonstrate the basic library functionality.

NOTE: On older versions of the Arduino IDE it may be necessary to re-start the IDE before the examples will be listed in the menu.

Be sure to also check out the [BuzzKill Arduino Library Guide](BuzzKill_Arduino_library_guide.pdf). It provides a much more detailed look at the library structure and syntax, and an in-depth summary of all available methods.

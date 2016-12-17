# Development

- [License file](LICENSE): MIT license is the open-source license of our choice.
- [Android gitignore](gitignore): the gitignore file for Android projects.
- Code style: Google's [Java style guide](https://google.github.io/styleguide/javaguide.html) is preferred. You can use your favorite IDE to clean up the code:
    + [IntelliJ](https://github.com/google/styleguide/blob/gh-pages/intellij-java-google-style.xml)
    + [Eclipse](https://github.com/google/styleguide/blob/gh-pages/eclipse-java-google-style.xml)
- Base identifier for our packages: `org.emot`

# Deployment

### The Phone

- **Nexus 5x**
- Android 7.0 (**API level 24**)
- Display: 5.2 inch, 1920 * 1080 at 423 ppi
- USB type-C connector

### Board

[Sparkfun Pro Micro](https://www.sparkfun.com/products/12640). Arduino-compatible.

- Chip: ATmega32U4.
- Specs: 32 KB programmable flash memory (for storing program, nonvolatile). 2.5 KB internal SRAM (run time memory, volatile). 1 KB EEPROM (nonvolatile storage).

### Emot Actuators

- Arms: left and right. Operations: set arms in 1 of 4 available positions (lower, low, up, upper)
- LED: 1 and 2. Operations: set on/off and color.
- pressure sensor: can detect touch within left or right side of the screen.

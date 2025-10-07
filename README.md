# Bulgarian Phonetic Keyboard Layout for macOS

## Introduction

This repository is dedicated to the Bulgarian Traditional Phonetic Keyboard layout for macOS, designed to simplify typing in Bulgarian by aligning Cyrillic letters to keyboard keys based on their phonetic sound.

Tested in the latest MacOS version: **macOS 14 Sonoma**

![](./bg-keyboard.png)



## Keyboard Layout Variants

This repository includes two keyboard layout files:

- **`KV-BG - Phonetic.keylayout`** - For standard ANSI keyboards (most US MacBooks and keyboards)
- **`KV-BG - Phonetic ISO.keylayout`** - For ISO keyboards (European MacBooks and external keyboards)

### Which layout should I use?

**Use the ISO layout if:**
- You have a European MacBook or external keyboard with an ISO layout
- The key to the left of "Z" is larger and positioned differently
- You're experiencing issues with the letter **ю** (yu) not appearing when pressing the key to the left of "1"

**Use the standard layout if:**
- You have a US MacBook or ANSI keyboard
- The key to the left of "1" works correctly for **ю** (yu)

The ISO layout fixes the missing **ю** letter issue that many Bulgarian Mac users with ISO keyboards experience.

## Installation on macOS

1. **Download the Layout File**
 
   Download either `KV-BG - Phonetic.keylayout` (for ANSI keyboards) or `KV-BG - Phonetic ISO.keylayout` (for ISO keyboards) based on your keyboard type.

2. **Install the Keyboard Layout**

   Copy the downloaded file to the `~/Library/Keyboard Layouts/` directory.

3. **Restart Your Mac**

   Restart your computer to ensure the new keyboard layout is recognized by the system.

4. **Activate the Layout**

   - Open `System Preferences > Keyboard > Input Sources`.
   - Click the `+` button and navigate to the "Others" section at the bottom of the list.
   - Look for **BG - Phonetic** and click "Add" to select it as one of your input methods.

## Usage

After restarting your Mac and adding the keyboard layout, select **BG - Phonetic** from the input source options in your system menu bar to start using it.

## Developer Support:

- If you saw some issue/bug 🐛
- If you want some new feature or change to be added/implemented. 😊

Please, contact the creator of **Bulgarian Phonetic Keyboard**, so he will be able to fix or improve it:

[Kristiyan Velkov](https://www.linkedin.com/in/kristiyan-velkov-763130b3/)

## Support my work

If you like my work and want to support me to work hard, please donate via:

[Revolut](https://revolut.me/kristiyanvelkov) OR [Buy me a coffee](https://www.buymeacoffee.com/kristiyanVelkov)  
Thanks a bunch for supporting me! It means a LOT 😍

## Contributing

Contributions are welcome. Feel free to submit pull requests or open issues for suggestions, improvements, or bug reports.

## Author

[Kristiyan Velkov](https://www.linkedin.com/in/kristiyan-velkov-763130b3/)

## License

Released under the [MIT License](LICENSE). See the LICENSE file for more details.

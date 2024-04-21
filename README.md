# win-mac-keyboard
A US Windows Keyboard with MacOS layout for special characters.

## Installation

Download and extract the installer from [releases](link). Run setup.exe. The installer will add a keyboard layout which can be selected with Windows + Space keys or from the tool bar.

![image](https://github.com/sean-parent/win-mac-keyboard/assets/2279724/ebdff1a9-d0b1-4201-a2d1-10a01c5bfb44)

## Usage

To access the characters, you can use the right-alt(altGr) key or control-alt keys along with shift.

![alt-key-screenshot](https://github.com/sean-parent/win-mac-keyboard/assets/2279724/38ba8459-0724-4286-858a-f7e21c2ebe77)

![image](https://github.com/sean-parent/win-mac-keyboard/assets/2279724/4885dc7a-39af-4a57-a1fd-c78accaf9adb)

The highlighted keys are combining characters and can be used with other vowels to add accents. For example, to type:

| character | keystroke |
|---|---|
| ́e | altGr-e, e |
| ́i | altgr-e, i |
| ̈o | altgr-u, o |
| ̃n | altgr-n, n |
| ̈a | altgr-u, a |

## Modifications

The keyboard is created using [Microsoft's Keyboard Layout Creator 1.4](https://www.microsoft.com/en-us/download/details.aspx?id=102134&irgwc=1). The source file is [hear](https://github.com/sean-parent/win-mac-keyboard/blob/main/source/US-macOSv0.klc). You can download the file or clone this repository to make your customizations.

## Known issues

The application must be Unicode aware, and the combining characters don't render correctly in some situations. In some cases, the characters interfere with application shortcuts. In such cases, you can toggle to the regular keyboard with Windows-Space. In some apps, altGr will not work for some characters, but control-alt will work.

If you have issues or suggestions, please open an issue in this repository.

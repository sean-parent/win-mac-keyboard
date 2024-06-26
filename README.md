# win-mac-keyboard
A US Windows Keyboard with macOS layout for special characters.

## Installation

Download and extract the installer from [releases](https://github.com/sean-parent/win-mac-keyboard/releases/tag/v1.0.0). Run setup.exe. The installer will add a keyboard layout that can be selected with the Windows + Space keys or from the toolbar.

![image](https://github.com/sean-parent/win-mac-keyboard/assets/2279724/ebdff1a9-d0b1-4201-a2d1-10a01c5bfb44)

## Usage

To access the characters, you can use the right-alt(altGr) key or control-alt keys along with shift.

![alt-key-screenshot](https://github.com/sean-parent/win-mac-keyboard/assets/2279724/38ba8459-0724-4286-858a-f7e21c2ebe77)

![image](https://github.com/sean-parent/win-mac-keyboard/assets/2279724/4885dc7a-39af-4a57-a1fd-c78accaf9adb)

The highlighted keys are combining characters and can be used with other vowels to add diacritical marks. The diacritical mark is typed after the character it is combined with. This is the opposite of how it is typed on macOS. Examples:

| character | keystroke |
|---|---|
| é | e, altGr-e |
| í | i, altGr-e |
| ö | o, altGr-u |
| ñ | n, altGr-n |
| ä | a, altGr-u |

## Modifications

The keyboard was created using [Microsoft's Keyboard Layout Creator 1.4](https://www.microsoft.com/en-us/download/details.aspx?id=102134&irgwc=1). The source file is [here](https://github.com/sean-parent/win-mac-keyboard/blob/main/source/US-macOSv0.klc). You can download the file or clone this repository to make your customizations.

## Known issues

The application must be Unicode-aware. In some cases, the characters interfere with application shortcuts. In such cases, you can toggle to the regular keyboard with Windows-Space. In some apps, altGr will not work for some characters, but control-alt will work.

If you have issues or suggestions, please open an issue in this repository.

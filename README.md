<div align="center">
  <a href="https://github.com/roeegh/Mise">
    <img src="assets/logo.png" alt="Logo" width="80" height="80">
  </a>
  
  <h3 align="center">Mise</h3>
  
  <p align="center">
    A collection of customizations ready to use with Cowabunga and FileSwitcherPro
  </p>
</div>

## Disclaimer

All of my customizations are exported from my iPhone 13 Pro Max running iOS 16.0. I cannot guarantee that all customization will work on your device. Some customizations are iOS-specific, please apply the appropriate ones.

## Prerequisites

1. Install Filza or Santander
2. Install Cowabunga or FileSwitcherPro
3. Create a folder named `roeegh` in the `/var/mobile/Documents` directory

## How to use it?

4. Download and unzip the `.zip` of the wanted customization(s) from the [releases](https://github.com/roeegh/Mise/releases/latest)
5. Move the file from the `Replacement` folder into the `/var/mobile/Documents/roeegh` folder
6. Import the `.cowperation` if you are using Cowabunga or `.fsp` if you are using FileSwitcherPro

## How to change the color?

1. Navigate to `/var/mobile/Documents/roeegh` using Filza or Santander
2. Open the file for the customization you want to edit and find the `red`, `green`, `blue`, and `alpha` fields
3. Take your wanted color value and divide it by 255 to get a decimal value, enter that value in its respective RGBA field

_Notice: Values <ins>*must*</ins> be between 0 and 1, otherwise you will respring every time you get a notification_

## Showcase

### Notification Shadow

Adds a colored shadow to Banners only and Bluetooth device pill

Original File Paths:

-   Light Mode: `/System/Library/PrivateFrameworks/PlatterKit.framework/platterVibrantShadowLight.visualstyleset`

-   Dark Mode: `/System/Library/PrivateFrameworks/PlatterKit.framework/platterVibrantShadowDark.visualstyleset`

<details><summary>Screenshots</summary>

|                                Light Mode                                 |                                Dark Mode                                 |
| :-----------------------------------------------------------------------: | :----------------------------------------------------------------------: |
| ![](</Notification Shadow/Images/Notification Shadow Banner (Light).png>) | ![](</Notification Shadow/Images/Notification Shadow Banner (Dark).png>) |
|  ![](</Notification Shadow/Images/Notification Shadow Pill (Light).png>)  |  ![](</Notification Shadow/Images/Notification Shadow Pill (Dark).png>)  |

</details>

### Custom Spacebar

Change the text of the spacebar on your keyboard

Original File Paths:

-   English: `/System/Library/TextInput/TextInput_en.bundle/Keyboard-en.plist`

_Notice: This file path is for the <ins>English language only</ins>, please change `TextInput_en.bundle` and `Keyboard-en.plist` with the correct one for your language_

<details><summary>Screenshots</summary>

|                                Light Mode                                |                                Dark Mode                                |
| :----------------------------------------------------------------------: | :---------------------------------------------------------------------: |
| ![](</Custom%20Spacebar/Images/Custom%20Spacebar%20Text%20(Light).png>)  | ![](</Custom%20Spacebar/Images/Custom%20Spacebar%20Text%20(Dark).png>)  |
| ![](</Custom%20Spacebar/Images/Custom%20Spacebar%20Emoji%20(Light).png>) | ![](</Custom%20Spacebar/Images/Custom%20Spacebar%20Emoji%20(Dark).png>) |

</details>

## Acknowledgments

-   [Logo from @nokoriichimei](https://twitter.com/nokoriichimei/status/1568203679995695106?s=20)

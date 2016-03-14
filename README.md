# SoDaReloaded Theme

Dark and light custom UI themes for Sublime Text 3 optimized for better readability.
The theme supports the new Sublime Text 3 icons for file types out of the box!

Project site: [https://github.com/Miw0/sodareloaded-theme](https://github.com/Miw0/sodareloaded-theme)

## Design

#### Dark variant

![SoDaReloaded Theme](https://raw.githubusercontent.com/Miw0/sodareloaded-theme/master/dark/example.png)

#### Light variant

![SoDaReloaded Theme](https://raw.githubusercontent.com/Miw0/sodareloaded-theme/master/light/example.png)

## Installation

SoDaReloaded Theme is designed to work with [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](https://packagecontrol.io/), you can easily install SoDaReloaded Theme via the `Package Control: Install Package` menu item. The Soda Theme package is listed as `Theme - SoDaReloaded` in the packages list.

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/Miw0/sodareloaded-theme/ "Theme - SoDaReloaded"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - SoDaReloaded`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below.

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry:

**Example Sublime Text User Settings for the dark variant**

    {
        "theme": "SoDaReloaded Dark.sublime-theme"
    }

**Example Sublime Text User Settings for the light variant**

    {
        "theme": "SoDaReloaded Light.sublime-theme"
    }

## Soda Special Configurations
#### Want to use Soda Classic Tabs?
No problem. Just add this line into your `Settings - User` file.

    "soda_classic_tabs": true
    
#### Want to use Soda Rectangular Scrollbars?
No problem. Just add this line into your `Settings - User` file.

    "soda_rect_scrollbars": true

## Color schemes in the design demo
The color scheme used in the light variant is _Katzenmilch_ and in the dark variant it is _Boneyfied_.
Both can be found in the package [Bubububububad and Boneyfied Color Schemes](https://packagecontrol.io/packages/Bubububububad%20and%20Boneyfied%20Color%20Schemes)

## License

SoDaReloaded Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.

The following details apply to the Creative Commons license "author specified" components:

Based on Soda Theme by Ian Hill (http://buymeasoda.com/)

<div id="header" align='center'>
    <img src='Images/Logos/Xana.svg' width="150px" style="margin-bottom:10px">
    <h1 style="
        border-bottom: none;
        font-weight: 900;
        color: #d4be98; 
        font-size: 2.5em; 
        margin-bottom: 10px">
        Tartarus</h1> 
    <h1 style="border-color:#d4be9855"></h1>
</div>

## ScreenShots
<div align="center">
  <img src="Images/Screenshots/global_screenshot1.png" width="75%">
  <img src="Images/Screenshots/global_screenshot2.png" width="75%">
  <img src="Images/Screenshots/global_screenshot3.png" width="75%">
</div>

## Table of Contents

- [ScreenShots](#screenshots)
- [Table of Contents](#table-of-contents)
- [General Information 💻](#general-information-)
- [Hardware specs ⚙️](#hardware-specs-️)
- [Wallpapers 🌃](#wallpapers-)
  - [Guweiz: Artstation](#guweiz-artstation)
- [Color Theme 🖌](#color-theme-)
  - [Material Gruvbox](#material-gruvbox)
- [Fonts 🖋](#fonts-)
  - [JetBrains Mono Nerd Font: Nerd Fonts](#jetbrains-mono-nerd-font-nerd-fonts)
  - [Custom Icomoon Font: Icomoon](#custom-icomoon-font-icomoon)
- [LightDM Mini Greeter 🔒](#lightdm-mini-greeter-)
- [Awesome 🪄](#awesome-)
- [Starship 🚀](#starship-)
- [Rofi Launcher 📤](#rofi-launcher-)
- [Rofi Power Menu🔋](#rofi-power-menu)
- [Rofi Network Menu 📡](#rofi-network-menu-)
- [Spicetify 📻](#spicetify-)
- [BetterDiscord](#betterdiscord)
- [Firefox StartPage 🏠](#firefox-startpage-)

## General Information 💻
- **OS:** EndeavourOS
- **Wallpapers:** Guweiz
- **Color Theme:** Material Gruvbox
- **Fonts:** JetBrains Mono Nerd Font, Custom Icomoon Font
- **Session Manager:** LightDM
- **LightDM Theme:** lightdm mini greeter
- **WM:** AwesomeWM
- **Compositor:** Picom
- **Terminal:** Kitty
- **Shell:** Fish
- **Fish Theme:** Starship
- **Application Launcher:** Rofi
- **Power Menu:** Rofi
- **Network Menu:** Rofi
- **Pdf Reader:** Zathura
- **Code Editor:** vscode
- **Spicetify:** Fluent
- **Discord:** BetterDiscord
- **Search Engine:** Firefox
- **Firefox HomePage:** PrettyCofee

## Hardware specs ⚙️
This is mentioned becouse I have a couple of specific configurations that only work with my computer
- **Two graphics cards (Intel integrated graphics and Nvidia external graphic card)**
- **Dual monitor setup**

**Note:** On my os configuration I only use the external graphic card

## Wallpapers 🌃
### Guweiz: [Artstation](https://www.artstation.com/guweiz)
Main | Secundary
:-------------------------:|:-------------------------:
|<img src="Images/Wallpapers/main-ultrawide.png"> | <img src="Images/Wallpapers/secundary-ultrawide.png">|
|[Original](Images/Wallpapers/main-wide.jpg)|[Original](Images/Wallpapers/secundary-wide.jpg)|

I modified them to change their ratio to 21:9 and fill my ultrawide screen and that makes the borders messy so if you want the full quality of the artist use the originals.

## Color Theme 🖌
### Material Gruvbox
<div align="center">
    <img src="Images/Utils/Color_preview.png" height="300px">
</div>

The original creators: [Material Gruvbox](https://github.com/sainnhe/gruvbox-material)

Base Xresources: [.Xresources](https://gist.github.com/Cardoso1994/5fbbf98603b44bc986ec18e607b7dbf1#file-xresources_gruvbox_material)

*This color theme is applied on all the apps I customize for this rice*

## Fonts 🖋
### JetBrains Mono Nerd Font: [Nerd Fonts](https://www.nerdfonts.com/font-downloads)
### Custom Icomoon Font: [Icomoon](./Icomoon/)
I really like to put details and reference tv shows and films I like, so I have created my own custom font with these references and I used them on the rice. You can do it too on [icomoon](https://icomoon.io/)

Preview:
<img src="Images/Utils/icomoon_preview.png">

You need to be careful with what nerd font you use because they can overlap between them, I only have tested with JetBrains.

The fastest way to install them is to put it on your
```~/.local/share/fonts/ttf/```
directory, as you can see on mine [./.local/share/fonts/ttf/](./.local/share/fonts/ttf/)

## LightDM Mini Greeter 🔒
Main repository: [LightDM Mini Greeter](https://github.com/prikhi/lightdm-mini-greeter)

Screenshots:
Preview | Wallpaper
:-------------------------:|:-------------------------:
|<img src="Images/Screenshots/lock-screen.png">|<img src="Images/Wallpapers/lightdm/background.png">|

If you want to apply the theme just install LightDM Mini Greeter following their instractions and use the [lightdm-mini-greeter.conf](./LightDM-Mini-Greeter/lightdm-mini-greeter.conf). Make sure you change the user and the background-image route:
```
...
# The user to login as.
user = <your-username>
# Whether to show the password input's label.
show-password-label = true
...
# An absolute path to an optional background image.
# The image will be displayed centered & unscaled.
background-image = "<your-own-route>"
# The screen's background color.
background-color = "#282828"
...
```
In my personal [LigthDM](./LightDM-Mini-Greeter/lightdm.conf) configuration I have a display-setup-script, this is only necesary if you need to for your graphics drives or screen setup and you need to adapt the script to your own needs. 

## Awesome 🪄 


## Starship 🚀
[The minimal, blazing-fast, and infinitely customizable prompt for any shell!](https://starship.rs/)

Screenshot:

<div align="center">
  <img src="Images/Screenshots/starship.png" width="75%">
</div>

If you don't want to use my own fish config make sure you launch starship in yours ```
starship init fish | source```. The only file you need to use this theme on starship is the [startship.toml](.config/starship.toml) located on ~/.config.

## Rofi Launcher 📤
Modified themes from [adi1090x/rofi](https://github.com/adi1090x/rofi) 

Screenshot:

<div align="center">
  <img src="Images/Screenshots/rofi-launcher.png" width="65%">
</div>

In my ```~/.config/rofi/``` I have all of his config and feel free to try all of his themes. The one I use and I modify is [~/.config/rofi/launchers/colorful/launcher.sh](.config/rofi/launchers/colorful/launcher.sh)

## Rofi Power Menu🔋
As the launcher I modified some themes from [adi1090x/rofi](https://github.com/adi1090x/rofi) 

Screenshot:

<div align="center">
  <img src="Images/Screenshots/rofi-powermenu.png" width="50%">
</div>

This one is located on my [~/.config/rofi/applets/menu/powermenu.sh](.config/rofi/applets/menu/powermenu.sh).

## Rofi Network Menu 📡
This rofi menu is from [P3rf/rofi-network-manager](https://github.com/P3rf/rofi-network-manager). As the other ones I only have changed the theme to fit into the rice.

I put all the repo on [~/.config/rofi/rofi-network-manager](.config/rofi/rofi-network-manager/).

## Spicetify 📻
For spicetify I used the [Fluent](https://github.com/williamckha/spicetify-fluent) theme with a custom [material gruvbox](.config/spicetify/Themes/Fluent/color.ini) I made.

Screenshot:

<div align="center">
  <img src="Images/Screenshots/spicetify.png">
</div>

## BetterDiscord

Theme: 
 - [ClearVision](https://betterdiscord.app/theme/ClearVision)

Plugins:
 - [Game Activity toggle](https://betterdiscord.app/plugin/GameActivityToggle)
 - [Joined At Date](https://betterdiscord.app/plugin/JoinedAtDate)
 - [Show Hidden Channels](https://betterdiscord.app/plugin/ShowHiddenChannels)
 - [Spotify Controls](https://betterdiscord.app/plugin/SpotifyControls)

Screenshot:

<div align="center">
  <img src="Images/Screenshots/betterdiscord.png">
</div>

And as all the other things the theme is modified in [~/.config/BetterDiscord/themes/ClearVision_v6.css](.config/BetterDiscord/themes/ClearVision_v6.theme.css)

If you want to use the same exact theme you need to upload the secundary wallpaper and link it with the url in the css file
```
  ...
	/* APP BACKGROUND */
	--background-shading: 40%; /* app background shading (0 for complete smoothness) [default: 100%] */
	--background-overlay: rgba(40, 40, 40, 0.7); /* app background overlay color/gradient [default: rgba(0, 0, 0, 0.6)] */
	--background-image: url(<your-url>); /* app background image (link must be HTTPS) [default: url(https://clearvision.gitlab.io/images/sapphire.jpg)]*/
	--background-position: center; /* app background position [default: center] */
	--background-size: cover; /* app background size [default: cover] */
	--background-repeat: no-repeat; /* app background repeat [default: no-repeat] */
  ...
``` 

## Firefox StartPage 🏠
The start page is [Fluidity](https://github.com/PrettyCoffee/fluidity) is all ready build and you only need to configure the [new tab](https://addons.mozilla.org/es/firefox/addon/new-tab-override/) extension and link to the live demo of the proyect.

Screenshot:

<div align="center">
  <img src="Images/Screenshots/homepage.png">
</div>

The gif I use the following [gif](https://media.giphy.com/media/3BwNcKOTAVWBa/giphy.gif) and the following colors:

| Class           | Color           |
| --------------- | --------------- |
| --bg-color      | #282828         |
| --default-color | #D4BE98         |
| --accent-color  | #7DAEA3         | 
| --accent-color2 | #A9B665         | 

And finally, you only need to fill with the links and categories you want to have.
# all-charms-mod

This mod adds support to create an overlay with all the equipped charms in Hollow Knight that can be used in OBS for streaming.

# Requirements
- Hollow Knight 1.5.78
- Modding API 1.5.78

## How to install

Unzip the [last release](https://github.com/carloslancha/all-charms-mod/releases/latest) .zip file in `HollowKnightPath/hollow_knight_Data/Managed/Mods` folder.

## How to integrate in OBS

- Add a new Browser source in your Scene.
- Select Local File
- Browse file `HollowKnightPath/hollow_knight_Data/Managed/Mods/AllCharms/overlay.html`
- Set size to 1920x1080px
- Enjoy

## How to customize the Overlay
- You can customize the position, size and other styles by editing the [styles.css](./AllCharms/Resources/styles.css) file.

## Preview

![image](https://user-images.githubusercontent.com/5803434/138606512-b9fc734d-69a2-49ec-8d60-5ab08283b1a0.png)

## For Devs
-	[Documentation for developers](./AllCharms/DEV.md)

## License

GNU GPLv3 License © Carlos Lancha.<br/>
[Twitch/Empaventuras](https://www.twitch.tv/empaventuras)
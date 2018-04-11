# Unreal-Engine-Logitech-Wheel-Plugin
A plugin to apply Logitech Steering Wheel for Unreal Engine

* Unreal Engine Version: 4.19 (Avaluable), should work in other version;
* Hardware: Logitech G29, Untest for others, should work technically.

## This Plugin is base on **drb1992's [POST](https://forums.unrealengine.com/community/community-content-tools-and-tutorials/110043-free-logitech-wheel-plugin)** on Unreal Engine Forums.
Made some change to work on Logitech G29 and use easier.
You can go follow the post for more information.

# Usage
1. Add the Plugin to your project/Plugins directory.
2. Find your Steering Wheel device index,and add
	```
	[LogitechWheelInput]
	LogitechWheelDeviceIndex=0 //your device index
	```
	to DefaultGame.ini
3. Build your project and active the plugin in your project.
4. Enjoy!

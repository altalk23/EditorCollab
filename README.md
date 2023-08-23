# Editor Collab

The ultimate live multiplayer editor collaboration tool! Get the [latest release (v1.12.8)](https://github.com/altalk23/EditorCollab/releases/tag/v1.12.8)! Go to [the Patreon](https://www.patreon.com/alk1m123) to be able to host levels!

Note: After a Geode version of MegaHack by Absollute gets released, Editor Collab standalone version for Windows will be discontinued. The reason for this is explained best by HJFod's explanation on [why BetterEdit v5 is Geode only](https://github.com/HJfod/BetterEdit/blob/main/docs/WhyGeode.md). I currently have a standalone release because that is what most people use right now, and having both versions will hopefully allow for a smooth transition from one to the other.

## About

**Editor Collab**, is a live multiplayer editor collaboration tool designed for all kinds of people from casual creators to megacollab hosts. While being one of its kind, Editor Collab provides you with all the functionality you would expect from a multiplayer editor tool. Just create an account and ask your friend for a level code and collab! By using the mod you accept the [EULA](https://github.com/altalk23/EditorCollab/blob/main/EULA.txt).

## Installation

If you are using Geode you can download the mod from the index, which is enough. For manual installation, see down below.

### Manual installation

You can download the client from [releases](https://github.com/altalk23/EditorCollab/releases/latest). If you have [Geode](https://github.com/geode-sdk/geode) set up on Windows, I would recommend using the Geode release, otherwise the standalone setup instructions are given below. For MacOS only Geode release exists, so you will need that.  

For Geode put the .geode file inside the geode/mods/ folder and the mod should start functioning.

For standalone Windows release, follow these steps:
- Extract EditorCollab-Resources.zip
- Move EditorCollab folder into Resources/ folder
- Put minhook.x32.dll inside the Geometry Dash folder if you don't have it already (if you are using any of HJFod's or matcool's mods you should have it)
- Load EditorCollab-Standalone.dll with a mod loader

## Help, Bugs, Crashes, Questions, Feature Requests

If you need any help with the mod, or encountered an issue, feel free to either message me on Discord (alk1m123#3076), or create a [Github issue](https://github.com/altalk23/EditorCollab/issues/new/choose).

## Usage

Go to the online screen to see the Editor Collab button. You can also find a setting to move the button to the side. Pressing the button will yield a menu. Top right is the account settings, there you can create an account, log into your account, change your password, or logout. If you got the host permissions from the Patreon, either message me on Discord or fill out the form sent to you so I can add your hosting features.

### Users

In the Editor Collab menu, you can see a box you can enter a code in. Get the 8 letter level code the host gives to you and paste it there. You can also see your last joined level which can use it to easily join back. When you are in the editor, there is a button on the top right of the pause menu, which gives you the user list.

### Hosts 

For hosts, when you open a level, you will see a button on the top right side of the screen, the share button. This button opens an menu that you can share your level from. "Share" button will share the currently opened level, and "Stop sharing" will stop the sharing of that level. The clipboard icon copies the level code to your clipboard. While you are still sharing the level, you can use the "Recover" feature to get a global undo and redo screen, in which you can change which actions are done.

You can leave your shared level at any time, and join back using the Editor Collab menu. Your hosted level is listed at the top, clicking will put you back in the level. You can also save a copy of the level to your levels list, and look at previous level snapshots for older automatic saves. Just press the save button and enter the level name to the textbox that appears.

The default sharing of the level determines who can join. Restricted means only the people you have whitelisted can join, viewer means people can join with the level code but can't edit, and editor means they can edit the level. In the next page of this menu, there is a user list. This is the whitelisted users and seperate from the default sharing. This means you can share your level with specific people and no one else can join even if they somehow found out the level code. This provides a secure way of collaborating with your users.

In the user list inside the pause menu, you will see X buttons next to the users. You can kick specific users using this feature.

## Credits

Developed by Alk1m123 (alk) with love and tears. Please support me!

 * [Patreon](https://www.patreon.com/alk1m123)

 * [Twitter](https://twitter.com/alk1m123)

 * [Reddit](https://www.reddit.com/user/alk1m123)

 * [Github](https://github.com/altalk23/)

### Third Party Libraries

 * [Geode](https://github.com/geode-sdk/geode) - [License](https://github.com/geode-sdk/geode/blob/main/LICENSE.txt)

 * [Websocketpp](https://github.com/zaphoyd/websocketpp) - [License](https://github.com/zaphoyd/websocketpp/blob/master/COPYING)

 * [Asio](https://github.com/chriskohlhoff/asio) - [License](https://www.boost.org/LICENSE_1_0.txt)

 * [fmt](https://fmt.dev/latest/index.html) - [License](https://github.com/fmtlib/fmt/blob/master/LICENSE.rst)

 * [picosha3](https://github.com/yawara/picosha3) - [License](https://github.com/yawara/picosha3/blob/master/LICENSE)

 * [Minhook](https://github.com/TsudaKageyu/minhook) - [License](https://github.com/TsudaKageyu/minhook/blob/master/LICENSE.txt)

 * [filesystem](https://github.com/gulrak/filesystem) - [License](https://github.com/gulrak/filesystem/blob/master/LICENSE)

 * [json](https://github.com/nlohmann/json) - [License](https://github.com/nlohmann/json/blob/develop/LICENSE.MIT)

 * [gzip-hpp](https://github.com/mapbox/gzip-hpp) - [License](https://github.com/mapbox/gzip-hpp/blob/master/LICENSE.md)

## Thanks

Huge thanks to the Geode Development team for making me not suffer porting the mod to Windows. Love you [HJfod](https://twitter.com/hjfod), [Mat](https://twitter.com/mateus44_/), [PoweredByPie](https://github.com/poweredbypie/), and other people who helped me in some capacity.

Also big thanks to you for using my mod, either as a user or host. I love you. <3

# Threere: The three deck skin for small laptop screens based on Deere

Skin with three decks designed to be used with mixer and deck controller (eg. Akai AMX and TouchOSC) with minimal wasted screen space. Reminescent of [this Serato DJ layout](http://dj.rane.com/files/products/Serato_DJ_View_Stack_700.png) (which has 2 decks).

![Screenshot of the skin](https://raw.githubusercontent.com/jasalt/mixxx-threere-theme/master/media/screenshot.png)
![Example setup](https://raw.githubusercontent.com/jasalt/mixxx-threere-theme/master/media/setup.jpg)

## Installation
As told in the [Mixxx documentation](https://www.mixxx.org/wiki/doku.php/creating_skins#skin_faq).

1. Close Mixxx.
2. Download & unzip "s.zip" and copy/symlink the whole unzipped folder "Threere" to the corresponding path:
  * Linux: `/usr/share/mixxx/skins/`
  ** sudo ln -s `pwd`/Threere /usr/share/mixxx/skins/
  * Windows: `C:\Program Files\Mixxx\skins`
  * MacOS `/Applications/Mixxx.app/Contents/Resources/skins` (or right click Mixxx.app and select "Show Package Contents" to show the path `Contents/Resources/skins`. 
3. Start Mixxx , goto "Preferences-->Interface" and select "Skin-->Threere"
   Make sure you have "Waveform Display-->Waveform" selected
   Save preferences with OK.
4. The new skin should now be displayed.


## Developer notes

Based on Deere theme from Mixxx 2.0 which was slimmed down to suit my preferences in a quick and rad fashion. The theme code itself is very well designed though and Mixxx documentation is great. Follow the commit log to get the idea, you'll grasp it quickly with some basic HTML/CSS knowledge.

Docs: https://www.mixxx.org/wiki/doku.php/creating_skins

Elementary OS is a Linux distribution based on Ubuntu. Up to now, elementary os has released 4 versions.
Loki is the 4th version i.e. the newest elementary distribution. Elementary OS is beautiful and lots of fans have contributed to make it more attractive. In this repository, I keep some creative resources of other friendly github users. Using these resources and follow the following instruction, we can get a macOS-style elementary Loki.

First download all the files to a local directory via:
<pre>
git clone https://github.com/UKeyboard/elementary-2-macos.git
</pre>

Then copy Arc theme to system or user theme direcory via:
<pre>
cd elementary-2-macos
cp -r themes/Arc ~/.local/share/themes/
or
sudo cp -r themes/Arc /usr/share/themes/
</pre>

Copy la-capitaine-icon-theme to system or user icon directory via:
<pre>
cd elementary-2-macos
cp -r icons/la-capitaine-icon-theme/ ~/.local/share/icons/
or 
sudo cp -r icons/la-capitaine-icon-theme/ /usr/share/icons/
</pre>

Then you need to adjust serival system setting to apply the theme and icon suite. For simplity, it is highly recommended to install elementary tweak toolkit.
To instal elementary tweak:
<pre>
sudo apt-add-repository ppa:philip.scott/elementary-tweaks
sudo apt update
sudo apt install elementary-tweak
</pre>

Now go to "setting->tweaks" to set GTK theme,icon and layout as I do:
![Texte alternatif](https://raw.githubusercontent.com/UKeyboard/elementary-2-macos/master/screenshot/Screenshot%20from%202017-04-27%2000.23.28.png "Tweaks-Setting")

Congrats! Enjoy it!


#### What's more
In order to customize the appearance of dock,copy dock theme file under plank-theme directory to system or user dock theme directory via:
<pre>
cd elementary-2-macos
cp -r plank-theme/Pantiva/ ~/.local/share/plank/
or 
sudo cp -r plank-theme/Pantiva/ /usr/share/plank/
</pre>
Then right click on the edge of dock to set dock preference.

#### Screenshots
![Texte alternatif](https://raw.githubusercontent.com/UKeyboard/elementary-2-macos/master/screenshot/Screenshot%20from%202017-04-26%2022.40.27.png "")
![Texte alternatif](https://raw.githubusercontent.com/UKeyboard/elementary-2-macos/master/screenshot/Screenshot%20from%202017-04-26%2022.38.52.png "")

#### References
* icons/la-capitaines-icon-theme --- https://github.com/keeferrourke/la-capitaine-icon-theme
* plank-theme/capeos --- https://github.com/fsvh/plank-themes
* plank-theme/pantiva --- https://github.com/fsvh/plank-themes


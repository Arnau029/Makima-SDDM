# Makima-SDDM
This is a theme for the [SDDM login manager](https://github.com/sddm/sddm)
 * You can customize it in [theme.conf](https://github.com/Arnau029/Makima-SDDM/blob/main/theme.conf).
 * Screen Resolution: 1920x1080
 * Anime=Makima(Chainsaw man)
# Previews
![Preview](https://github.com/Arnau029/Makima-SDDM/blob/main/Previews/Left.png)
![Preview](https://github.com/Arnau029/Makima-SDDM/blob/main/Previews/Center.png)
![Preview](https://github.com/Arnau029/Makima-SDDM/blob/main/Previews/Right.png)
# Dependencies
> [!IMPORTANT]
> You need to download the dependencies for the configuration to work.
* You need donwload **sddm,noto-fonts-cjk,otf-ipafont**(Comands for arch).
<pre>sudo pacman -S sddm noto-fonts-cjk
yay -S otf-ipafont</pre>
# Install
1. Clone this repository 
<pre>sudo git clone https://github.com/Arnau029/Makima-SDDM.git</pre>
2. Move to <code>/usr/share/sddm/themes/</code>
<pre>sudo mv Makima-SDDM /usr/share/sddm/themes</pre>
3. Then edit <code>/etc/sddm.conf</code>and change it to look like this:
<pre>[Theme]
#Current the name
Current=Makima-SDDM
</pre>
# Credits
Based in the files of [Sugar Dark](https://github.com/MarianArlt/sddm-sugar-dark) By ***MariaArtl***

# My Ubuntu-setup

## Prerequisites for the Desktop environment

### System
- [Ubuntu version 18.04 min download it here](https://ubuntu.com/download/desktop)
### Packages
- **ubuntu-unity-desktop**
[here some help](https://linuxconfig.org/ubuntu-20-04-unity-desktop)
- **unity-tweak-tool**
- **gnome-tweak-tool**
- **Plank**, a customable dock application
- **Synapse**, a  semantic launcher, [here](https://launchpad.net/synapse-project)
- **Terminator**, a customable terminal emulator, [here to see how to install the color schemes](https://github.com/EliverLara/terminator-themes)
```sh
sudo apt install -y plank \
                    synapse \
                    unity-tweak-tool \
                    gnome-tweak-tool
```
- **Meteo**, [for more information](https://gitlab.com/bitseater/meteo)
- **System Load Indicator**, [For more information](https://launchpad.net/~indicator-multiload/+archive/ubuntu/stable-daily)

### Themes

- **X-Arc-Collection** as desktop scheme, [here it is](https://www.gnome-look.org/p/1167049/)
- **Azeny** as Plank scheme [For Plank](https://www.gnome-look.org/p/1463576/)
- **Capitaine Cursors** as cursos scheme, [here it is](https://www.gnome-look.org/p/1148692/)
- **Ultra Flat Icons** as desktop icon pack, [here it is](https://www.gnome-look.org/p/1171748/)

### Setting up everythinkg

![launcher](/.attachments/Selection_004.png)
![ubuntu](/.attachments/Selection_006.png)
![unity-tweak-tools-panel](/.attachments/Selection_005.png)
Attentions : Here you need to disable Invoke HUD if you want to use the "Super" key for anything else.
![unity-tweak-tools-panel](/.attachments/Selection_007.png)
![unity-tweak-tools-panel](/.attachments/Selection_008.png)

Now after you have downloaded all the Schemes dependencies, you can uncompress them and move each of them to their respective folder and dont forget to remove the compressed useless files : 

```
tar -xvf Ultra-Flat.tar.xz \
        rm Ultra-Flat.tar.xz \
        && mv Ultra-Flat* /usr/share/icons

tar -xvf X-Arc-Collection-v1.4.9.zip \
        && rm X-Arc-Collection-v1.4.9.zip
        && sudo mv X-Arc-* /usr/share/themes

tar -xvf Azeny.tar.gz \
        && rm Azeny.tar.gz \
        && mv Azeny ~/.local/share/plank/themes

tar -xvf capitaine-cursors-r4.tar.gz \
        && rm capitaine-cursors-r4.tar.gz \
        && sudo mv -vf capitaine-cursors /usr/share/icons
```

![unity-tweak-tools-panel](/.attachments/Selection_009.png)
![unity-tweak-tools-panel](/.attachments/Selection_010.png)
![unity-tweak-tools-panel](/.attachments/Selection_011.png)
![unity-tweak-tools-panel](/.attachments/Selection_012.png)

To change Plank's theme, you need to "ctrl"+ **right click** on the Plank's dock.

![unity-tweak-tools-panel](/.attachments/Selection_013.png)
![unity-tweak-tools-panel](/.attachments/Selection_014.png)

At this point you should have something like this:

![unity-tweak-tools-panel](/.attachments/Selection_015.png)

> Make sure that at this point Plank is runed at computer startup

If you want to use **Synapse**, by default the keyboard shortcuts is **"ctrl"** + **"space"** but you can change as you like.

My current Synapse theme is **Virglio**
![unity-tweak-tools-panel](/.attachments/Selection_016.png)

If like me you want to use the "super"+"space" keyboard shortcuts, you have to disable it first in the system keyboard shortcuts



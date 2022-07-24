# io.elementary.sideload.AppImage
AppImage of the "Sideload" utility from elementaryOS that installs Flatpaks from Flathub by pressing the "Install" button on any browser

# Requirements
- flatpak
- libflatpak0
- libgranite6

# Sources
- Original source https://launchpad.net/~elementary-os/+archive/ubuntu/stable/+sourcepub/12720625/+listing-archive-extra
- Original deb package [io.elementary.sideload_6.0.2+r795+pkg10~ubuntu6.1_amd64.deb](https://launchpad.net/~elementary-os/+archive/ubuntu/stable/+files/io.elementary.sideload_6.0.2+r795+pkg10~ubuntu6.1_amd64.deb)

# Installation
1. Download the AppImage and put it into a $PATH, for example /usr/local/bin, and made it executable:

       sudo wget https://github.com/ivan-hc/io.elementary.sideload.AppImage/releases/download/6.0.2/io.elementary.sideload-x86_64.AppImage -O /usr/local/bin/io.elementary.sideload
       sudo chmod a+x /usr/local/bin/io.elementary.sideload
     
2. Place the *.desktop file in ~/.local/share/applications

       mkdir -p ~/.local/share/applications && wget https://raw.githubusercontent.com/ivan-hc/io.elementary.sideload.AppImage/main/io.elementary.sideload.desktop -O ~/.local/share/applications/ && chmod a+x ~/.local/share/applications/io.elementary.sideload.desktop
       
3. Place the io.elementary.sideload.svg icon in ~/.local/share/icons

       mkdir -p ~/.local/share/icons/ && wget https://raw.githubusercontent.com/ivan-hc/io.elementary.sideload.AppImage/main/io.elementary.sideload.svg -O ~/.local/share/icons/
       
4. Go to https://flathub.org and click the "Install" button of an app you're interested in and select "Sideload" to open the file. If this does not work, right-click on the downloaded .flatpakref file (only the first time) to enable Sideload as the default app for this extension.

# Alternative solution
For an alternative way to open flatpakref files, visit [github.com/ivan-hc/flatpak-install-action](https://github.com/ivan-hc/flatpak-install-action)

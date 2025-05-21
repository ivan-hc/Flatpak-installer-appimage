# io.elementary.sideload.AppImage
AppImage of the "Sideload" utility from elementaryOS that installs Flatpaks from Flathub by pressing the "Install" button on any browser.

NOTE, this AppImage may not work. Consider it a prototype.

# Installation
1. Download the AppImage and put it into a $PATH, for example /usr/local/bin, and made it executable:
```
sudo wget https://github.com/ivan-hc/io.elementary.sideload.AppImage/releases/download/6.0.2/io.elementary.sideload-x86_64.AppImage -O /usr/local/bin/io.elementary.sideload
sudo chmod a+x /usr/local/bin/io.elementary.sideload
```
2. Place the *.desktop file in ~/.local/share/applications
```
mkdir -p ~/.local/share/applications && wget https://raw.githubusercontent.com/ivan-hc/io.elementary.sideload.AppImage/main/io.elementary.sideload.desktop -O ~/.local/share/applications/io.elementary.sideload.desktop && chmod a+x ~/.local/share/applications/io.elementary.sideload.desktop
```
3. Place the io.elementary.sideload.svg icon in ~/.local/share/icons
```
mkdir -p ~/.local/share/icons/ && wget https://raw.githubusercontent.com/ivan-hc/io.elementary.sideload.AppImage/main/io.elementary.sideload.svg -O ~/.local/share/icons/io.elementary.sideload.svg
```
4. Go to https://flathub.org and click the "Install" button of an app you're interested in and select "Sideload" to open the file. If this does not work, right-click on the downloaded .flatpakref file (only the first time) to enable Sideload as the default app for this extension.

# Alternative solution
For an alternative way to open flatpakref files, visit [github.com/ivan-hc/flatpak-install-action](https://github.com/ivan-hc/flatpak-install-action)

------------------------------------------------------------------------

## Install and update it with ease

### *"*AM*" Application Manager* 
#### *Package manager, database & solutions for all AppImages and portable apps for GNU/Linux!*

[![Istantanea_2024-06-26_17-00-46 png](https://github.com/ivan-hc/AM/assets/88724353/671f5eb0-6fb6-4392-b45e-af0ea9271d9b)](https://github.com/ivan-hc/AM)

[![Readme](https://img.shields.io/github/stars/ivan-hc/AM?label=%E2%AD%90&style=for-the-badge)](https://github.com/ivan-hc/AM/stargazers) [![Readme](https://img.shields.io/github/license/ivan-hc/AM?label=&style=for-the-badge)](https://github.com/ivan-hc/AM/blob/main/LICENSE)

*"AM"/"AppMan" is a set of scripts and modules for installing, updating, and managing AppImage packages and other portable formats, in the same way that APT manages DEBs packages, DNF the RPMs, and so on... using a large database of Shell scripts inspired by the Arch User Repository, each dedicated to an app or set of applications.*

*The engine of "AM"/"AppMan" is the "APP-MANAGER" script which, depending on how you install or rename it, allows you to install apps system-wide (for a single system administrator) or locally (for each user).*

*"AM"/"AppMan" aims to be the default package manager for all AppImage packages, giving them a home to stay.*

*You can consult the entire **list of managed apps** at [**portable-linux-apps.github.io/apps**](https://portable-linux-apps.github.io/apps).*

## *Go to *https://github.com/ivan-hc/AM* for more!*

------------------------------------------------------------------------

| [***Install "AM"***](https://github.com/ivan-hc/AM) | [***See all available apps***](https://portable-linux-apps.github.io) | [***Support me on ko-fi.com***](https://ko-fi.com/IvanAlexHC) | [***Support me on PayPal.me***](https://paypal.me/IvanAlexHC) |
| - | - | - | - |

------------------------------------------------------------------------

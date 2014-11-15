## Dynamix v3.0.0 BETA - USE AT YOUR OWN RISK

#### Update

*Dynamix webGui has been updated to version 3.0.0. Thanks to the support of the unRAID community a number of fixes and improvements are introduced. See the folder "changes" for a list of what has been changed, including changes in the optional plugins. All users of earlier versions are encouraged to upgrade to this version.*

#### Introduction

Dynamix webGui is a dynamic webGui for unRAID systems with enhanced features and optional add-ons.

Dynamix is a spin-off of the original [SimpleFeatures webGUI](http://lime-technology.com/forum/index.php?topic=12698) and is the next step in the evolution of the development of an enhanced webGui for unRAID systems.
Its goal is to have pages dynamically updated and watch the operation of your unRAID server in real-time.

Dynamix webGui offers a number of improvements not available before:

- Real-time page updates, the status view of your array is always up-to-date.
- Tabbed viewing, more efficient use of the available screen area, scrolling is hardly required.
- Improved visibility, better readibility and consistency of the sans-serif and monospace fonts in different browsers.
- Improved operability, no more accidental cancellations or wrong button clicking.
- Fully compatible with unRAID OS v6.0 beta 10

Dynamix webGui completely replaces the stock unRAID GUI which comes with version 6.0 or the enhanced Limetech webGui on github.

Do **not** use Dynamix webGui on any versions of unRAID other then 6.0 beta 10

Do **not** run Dynamix in conjunction with the Limetech enhanced webGui, these are not compatible.

Do **not** mix Dynamix and SimpleFeatures plugins, these are not compatible.

Dynamix webGui requires an up-to-date browser version. It has been tested with the latest versions of Internet Explorer, Chrome, Firefox and Safari.

#### Download warning

*DO NOT DOWNLOAD FILES DIRECTLY FROM THE FOLDERS 'DOWNLOAD' OR 'PLUGINS' BUT USE THE LINKS PROVIDED IN THIS 'README.MD' FILE INSTEAD.*

#### Installation

*This describes a first time installation, if you are upgrading from an older version, see the section 'Upgrading'.*

Dynamix webGui is considered a system plugin and is installed in the folder `/boot/plugins`.
This ensures it gets installed first, before any other plugins, and the correct environment is created upfront.

- Login to the command line on your server, e.g., at the console or a telnet session.
- Create the directory `/boot/plugins` directory, if it is not existing.
- Type the below:

```
cd /boot/plugins
wget --no-check-certificate https://raw.github.com/Jencryzthers/dynamix/master/unRAIDv6/ (plugin name) .plg
```

- Alternatively: [![](/download/dynamix.webGui.png)](https://raw.github.com/Jencryzthers/dynamix/master/unRAIDv6/ (plugin name) .plg) (right-click and select "save link as")

- Reboot your server to start with a *clean* webGui environment.
- You may need to clear your Browser's cache for correct viewing.



## Dynamix

DYNAMIX is a dynamic webGui for unRAID with enhanced features and optional add-ons.

DYNAMIX is the next step in the evolution of the original SimpleFeatures enhanced webGui for unRAID systems.
Its goal is to have pages dynamically updated and watch the operation of your unRAID server in real-time.

DYNAMIX offers a number of improvements not available before:

- Real-time page updates, the status view of your array is always up-to-date.
- Tabbed viewing, more efficient use of the available screen area, scrolling is hardly required.
- Improved fonts, better readibility and consistency of the sans-serif and monospace fonts in different browsers.
- Improved operability, no more accidental cancellations or wrong button clicking.

#### Overview

DYNAMIX completely replaces the stock unRAID GUI which comes with version 5.0, do **not** use Dynamix on any prior versions - including
the earlier RC candidates.

Do **not** mix Dynamix and SimpleFeatures plugins, these are not compatible.

#### Installation

DYNAMIX is considered a system plugin and is installed in the folder `/boot/plugins`.
This ensures it gets installed first, before any other plugins, and created the correct environment.

- First, login to the command line on your server, e.g., at the console or a telnet session.
- Next, make sure you have a `/boot/plugins` directory.  If it already exists, **ensure that it's empty**.
- Now type this:

```
cd /boot/plugins
wget --no-check-certificate https://github.com/bergware/dynamix/raw/master/download/dynamix.webGui-2.0.0-noarch-bergware.plg
installplg dynamix.webGui-2.0.0-noarch-bergware.plg
```

- Reboot your server to start with a *clean* webGui environment.

#### Screenshots

The main screen shows the different devices in separate tabs. Click on the header to move between them.

![](/screenshot/main-array.png)

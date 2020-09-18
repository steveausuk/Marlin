# Marlin 2 3D Printer Firmware

This fork contains my personal version of marlin 2 intended for use with geeetech and bear brand printers.

This being said nearly all the 100k+ lines of code i added have been merged upstream offical to marin 2.

At this time there is nearly no differance between my fork and upstearm other then my custom configuration files (configuration.h, configuration_adv.h, start_here.h).

# Supported Models

A10 and its variants

A20 and its variants

A30 and its variants

I3PRO and its variants

E180
D200
M201
Ender3

# Code Contributed
Upstream marlin 2 repo: https://github.com/MarlinFirmware/Marlin/pulls?q=author%3AVertabreak+

Configuration repo: https://github.com/MarlinFirmware/Configurations/pulls?q=author%3AVertabreak+

## Building Marlin 2.0

To build Marlin 2.0 you'll need [PlatformIO](https://docs.platformio.org/en/latest/ide.html#platformio-ide). We've posted detailed instructions on [Building Marlin with PlatformIO for ReArm](https://marlinfw.org/docs/basics/install_rearm.html) (which applies well to other 32-bit boards).

## Credits

The current Marlin dev team consists of:

 - Scott Lahteine [[@thinkyhead](https://github.com/thinkyhead)] - USA &nbsp; [Donate](https://www.thinkyhead.com/donate-to-marlin) / Flattr: [![Flattr Scott](https://api.flattr.com/button/flattr-badge-small.png)](https://flattr.com/submit/auto?user_id=thinkyhead&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)
 - Roxanne Neufeld [[@Roxy-3D](https://github.com/Roxy-3D)] - USA
 - Chris Pepper [[@p3p](https://github.com/p3p)] - UK
 - Bob Kuhn [[@Bob-the-Kuhn](https://github.com/Bob-the-Kuhn)] - USA
 - João Brazio [[@jbrazio](https://github.com/jbrazio)] - Portugal
 - Erik van der Zalm [[@ErikZalm](https://github.com/ErikZalm)] - Netherlands &nbsp; [![Flattr Erik](https://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)

## License

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.

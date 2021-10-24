
FXLOAD UTILITY

This program is conveniently able to download firmware into FX, FX2,
FX2LP, and FX3 EZ-USB devices, as well as the original AnchorChips
EZ-USB. It is intended to be invoked by hotplug scripts when the
unprogrammed device appears on the bus.

Primarily as an aid for developers, this can also be used to update
firmware on devices which boot from I2C serial EEPROMs.  For that
use, as well as downloading firmware to all other off-chip memory,
a second stage loader must first be downloaded. This is currently not
supported on the FX3.

The distribution includes "a3load.hex", which is a simple second stage
loader that works with all the EZ-USB products listed above.  If you
want to write to an EEPROM, you can use the appropriate version of the
"Vend_Ax" code provided with the Cypress developer kit.


UPDATES

See the repoitory page at https://bitbucket.org/DJOConnor/fxload

Post any bug reports to darius@dons.net.au

If you modify the code, the GPL requires that you make your updates
generally available (under most circumstances).  Providing them in the
form of patches against the current CVS ("cvs diff -u"), or the last
release ("diff -u old new") is most useful, since otherwise it's awkward
to integrate such changes into the standard distribution.


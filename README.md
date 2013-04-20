Schematics and accompanying documentation for the UmTRX project
===============================================================

UmTRX is a dual-channel wide-band SDR transceiver with 1GbE connection. It is developed by [Fairwaves] team to be used as a transceiver for [OpenBTS] and [OsmoBTS] GSM base stations, but due to its SDR nature it could be used for many other applications as well.

For more details visit the project web-site: http://code.google.com/p/umtrx/

[Fairwaves]: http://www.fairwaves.ru/
[OpenBTS]: https://wush.net/trac/rangepublic/
[OsmoBTS]: http://openbsc.osmocom.org/trac/wiki/OsmoBTS

Structure
---------

- umtrx-v2 - files related to UmTRXv2 boards
  - altium - design files in Altium Designer format
  - bom - Bill of Materials exported from the Altium Designer
  - pdf - schematics and assembly drawings exported from the Altium Designer
  - pictures - 3D model pictures and photos
- umtrx-v2.1 - files related to UmTRXv2.1 boards
  - altium - design files in Altium Designer format
  - bom - Bill of Materials exported from the Altium Designer
  - pdf - schematics and assembly drawings exported from the Altium Designer
  - pictures - 3D model pictures and photos
- umsel-v1 - files related to UmSELv1 preselector mezzanine boards (GSM900 and GSM1800 versions)
  - altium - design files in Altium Designer format
  - bom - Bill of Materials exported from the Altium Designer
  - gerber - PCB layout in the Gerber format
  - NC Drill - drill files for manufacturing
  - pdf - schematics and assembly drawings exported from the Altium Designer
  - Pick Place - pick and place files for manufacturing
  - pictures - 3D model pictures and photos

Note: PCB layout for new UmTRX versions are published when we start selling this version. Prior to that it's available per request to our partners.

License
-------

All design files, including schematics and PCB layout are licensed under Creative Commons Attribution-ShareAlike 3.0 license [CC-BY-SA 3.0].

In few words, it means, that you're free to copy, distribute and adapt the work both for commercial and non-commercial use, under the condition that you attribute the original project and distribute the derived work under the same or a compatible license.

For a full legal text of the license please refer to the [Creative Commons web-site][CC-BY-SA 3.0].

**Note**: We're looking at the [CERN Open Hardware License][OHL] and will probably switch to it when dust settles around it a bit.


[CC-BY-SA 3.0]: http://creativecommons.org/licenses/by-sa/3.0/
[OHL]: http://www.ohwr.org/projects/cernohl/wiki/

Datasheets
----------

* Most datasheet are easily found at the respective manufacturers' web-sites.
* Datasheets for Lime Microsystems LMS6002D single-chip transceiver could be found at the lms6002-documentation github repository: https://github.com/chemeris/lms6002-documentation

# IOB-Baseboard
## License: CERN Open Hardware Licence v1.2

IOB Baseboard - wiring termination and I2C / Power bus management

The latest in the evolution of the perfect layout I/O system...
Previous I2C-xxx designs either let to a proliferation of adapters
(current sink, input filters...) and to less than robust mechanical
designs (daughtercards that easily pulled out of their sockets with
cable movement)

This version does 4 things:
 * All wiring is terminated into mechanically stable connection points
 * There are personality adapters to account for the level shifting, buffering and other I/O line adaptions that may be needed
 * While I like having blinking LED lights on every I/O line for debugging, others do not - so there is now a plug-in LED monitor slot for each set of 4x I/O lines
 * A generic I2C Expander plug in footprint.

I have built several board variations for various different I2C
Expander chips to take advantage of unique addressing, I/O levels,
cost, etc - with the only thing changing between boards being the
chip related stuff.  Maintaining and stocking several "slightly
different" board designs gets expensive, both from both inventory
and support perspectives.

V1.0 is a prototype that seeks to validate the basic modular assumptions I'm making.



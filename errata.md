Rev 1.0
========
Major
---------
- T1 pinout wrong. workaround: cut thermals to pin 4
- D6, D7, D8 connected to wrong node. workaround: leave them out
- T3, T4, T5, T6 drain and source swapped

Minor
------
- JTAG traces should not go through the connector pads (in case pads get destroyed)
- Holes for through hole components should have larger annular rings
- FT2232D was most likely a bad idea

BOM errors
-----------
- T2 has wrong footprint. AON7534 happens to fit on this footprint by pure chance.
- S1 does not fit footprint
- C194, C195, C196, C197 should be 0603, not 0402

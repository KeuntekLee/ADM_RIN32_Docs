Process Input / Output Areas
=====

.. _readcoils:
.. _readholdingregisters:
.. _readdiscreteinputs:

Input Area
------------

To use Lumache, first install it using pip:

<div align="center">
+------------+------------------+-----+-------------------+
| Coil (Bit) | Holding Register | Bit | Process Data Area |
+============+==================+=====+===================+
|    0000h   |       0000h      |  0  |     0000-0001h    |
+------------+                  +-----+                   |
|    0001h   |                  |  1  |                   |
+------------+                  +-----+                   |
|    0002h   |                  |  2  |                   |
+------------+                  +-----+                   |
|    0003h   |                  |  3  |                   |
+------------+                  +-----+                   |
|     ...    |                  | ... |                   |
+------------+                  +-----+                   |
|    000Fh   |                  |  15 |                   |
+------------+------------------+-----+-------------------+


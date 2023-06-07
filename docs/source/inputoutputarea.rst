Process Input / Output Areas
=====

.. _readcoils:
.. _readholdingregisters:
.. _readdiscreteinputs:

Input Area
------------

The input area start from 0x000 to 0x1BF, which total size of 448 bytes (224 words).

Bits (Coils) and Register in the input area can be described as below.


+------------+------------------+-----+-------------------+
| Coil (Bit) | Holding Register | Bit | Process Data Area |
+============+==================+=====+===================+
|    0000h   |       0000h      | \ 0 |     0000-0001h    |
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

Output Area
------------

The output area start from 0x0200 to 0x3BF, which total size of 448 bytes (224 words).

Bits (Coils) and Register in the output area can be described as below.

+------------+------------------+-----+-------------------+
| Coil (Bit) | Holding Register | Bit | Process Data Area |
+============+==================+=====+===================+
|    0000h   |       0000h      | \ 0 |     0200-0201h    |
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


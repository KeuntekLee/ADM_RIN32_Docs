Process Input / Output Areas
=====

.. _readcoils:
.. _readholdingregisters:
.. _readdiscreteinputs:

Input Area
------------

To use Lumache, first install it using pip:

.. table:: Optional Caption
    
    
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

.. list-table:: Title
   :widths: 25 25 50
   :header-rows: 1
   :column-alignment: left center right

   * - Heading row 1, column 1
     - Heading row 1, column 2
     - Heading row 1, column 3
   * - Row 1, column 1
     -
     - Row 1, column 3
   * - Row 2, column 1
     - Row 2, column 2
     - Row 2, column 3

dump_gdbtable
=============

Python script to dump the content of a .gdbtable according
to the reverse engineered [FileGDB specification](https://github.com/rouault/dump_gdbtable/wiki/FGDB-Spec)

Directions
==========

Running

    ./dump_gdbtable.py 001.gdb/a00000011.gdbtable

extracts the raster stored in the indicated gdbtable. Work is still needed to
generalize this.

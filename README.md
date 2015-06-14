# CMOC

A C library for MOC (Multi-Order Coverage map) wich is “inspired” from the Java library

A library which provides:
- Reading of a FITS, JSON and CSV (catalogues) 
- Writing in FITS and JSON
- Operations (union, difference, etc.)
- Equality checking
- Adding of a disk into a MOC
- Checking if the MOC is included in a circle
- Intersection between a circle and a MOC

The C library “is” around 60% faster than the Java library (benchmark with 1000 unions, 1000 intersections, 1000 differences)



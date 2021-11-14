# VBA-MGRS-to-LatLong
This VBA code provides 6 functions to convert between MGRS, UTM, and Decimal Degrees Latitude Longitude.

Provided functions are: MGRS2LL, MGRS2UTM, UTM2MGRS, UTM2LL, LL2MGRS, LL2UTM

They accept/return coordinates in number/letter arrays:
    MGRS example: Array(31, "U", "D", "Q", 48251, 11932)
    UTM example: Array(31, 'N', 448251, 5411932))
    LatLong example: Array(48.8582, 2.2945)

The code is translated from javascript code here: http://www.movable-type.co.uk/scripts/latlong-utm-mgrs.html / https://github.com/chrisveness/geodesy



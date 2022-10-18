# BDF to adafruit

Converts BDF generated files with [gbdfed](http://sofia.nmsu.edu/~mleisher/Software/gbdfed/) to a format that can be used with the adafruit GFX Library.

 - It assumes a fix max width of 16. Zero fills right
 - Does not require that all glyphs are defined
 - Uses FONT name defined in BDF
 - Outputs working .h file
 - Added extended comments (ASCII character)
 - Assumes glyphs 0 to 127 only

### Usage: 
```
./bdf2adafruit.py somefont.bdf > somefont.h
```

### Credit:
Based on original version from William Skellenger https://github.com/adafruit/Adafruit-GFX-Library/blob/master/fontconvert/bdf2adafruit.py

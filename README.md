# FontConvert

Use this tool to create custom fonts from TTF fonts to the Adafruit_GFX library format. 

1. Copy the desired font to your FontConvert folder (not necessary but simplifies command line typing)
2. Launch a command prompt 
3. In the command prompt window navigate to your font convert folder
4. type FontConvert FontFileName.ttf YourDesiredFontSize OptionalStartingASCIIChar OptionalEdingASCIIChar > YourDesiredName.h
5. Move the new .h file to your Adafruit_GFX\Font folder
6. Include the font name in your .ino (#include "fonts\YourDesiredName.h"
7. xxx.setFont(&HFileGFXFontName) // or whatever the const GFXfont name is

Virus free as of 8/22/2022 Using TrendMicro 21.600.1005

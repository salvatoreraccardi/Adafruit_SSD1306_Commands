# Adafruit_SSD1306_Commands
This document lists all the functions of the Adafruit_SSD1306 library
[GitHub - ADAFRUIT](https://github.com/adafruit/Adafruit_SSD1306/blob/master/Adafruit_SSD1306.cpp)

## Generic functions

**Clear display**
```
display.clearDisplay();
```
**Init**
```
display.display();
```
**Draw pixel**
Pixel_color: SSD1306_BLACK | SSD1306_WHITE | SSD1306_INVERT.
```
display.drawPixel(X, Y, color);
```
**DrawFastHLine**
```
display.drawFastHLine(X, Y, WIDTH, color);
```
**DrawFastHLineInternal**
```
display.drawFastHLineInternal(X, Y, WIDTH, color);
```
**drawFastVLine**
```
display.drawFastHLineInternal(X, Y, HEIGHT, color);
```
**DrawFastVLineInternal**
```
display.drawFastVLineInternal(X, Y, HEIGHT, color);
```

**InvertDisplay**
```
display.invertDisplay();
```

## Return value

**GetPixel**
```
display.getPixel(X, Y);
```
**GetBuffer** - Get base address of display buffer for direct reading or writing
```
display.getBuffer();
```

## Scrolling functions

**Startscrollright / Startscrollleft**
```
display.startscrollright(START , STOP);
```
OR
```
display.startscrollleft(START , STOP);
```

**Startscrolldiagright / Startscrolldiagleft**
```
display.startscrolldiagright(START , STOP);
```
OR
```
display.startscrolldiagleft(START , STOP);
```

**Stopscroll**
```
display.stopscroll();
```

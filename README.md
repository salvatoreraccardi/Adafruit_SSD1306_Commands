# Adafruit_SSD1306_Commands
This document lists all the functions of the Adafruit_SSD1306 library

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

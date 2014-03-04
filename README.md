#ColorCycle
Color cycle generates RGB values, cycling through a sequence of colors. The colors are generated from a sine function with variable offsets for each RGB value. The frequency with which the ColorCycle changes colors and the opacity of the colors is also controllable via the constructor function.

##ColorCycle Constructor Function
```
ColorCycle(float frequency, float offsetRed, float offsetGreen, float offsetBlue, float alpha)
ColorCycle() //Uses default values
```
### frequency
The frequency with which the colors change. The default value is 1.

### offsetRed, offsetGreen, offsetBlue
A numeric offset that creates a sequence of colors to cycle through.

*Red default value: 0
*Green default value: 2
*Blue default value: 4

### alpha
A number between 0 and 255 that controls the opacity of the color
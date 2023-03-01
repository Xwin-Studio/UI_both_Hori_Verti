# UI_both_Hori_Verti
Making UI can show both Horizontal and Vertical

Only use this when docking can't show your UI right way. Otherwise use docking cause it easy.

This video will show you a method make your UI can show both Horizontal and Vertical screen.
Like this

The Ideas is save Rectransform of each UI element then set it back when screen is horizontal or vertical.

First you need design you UI both vertical and horizontal.
This Scriptable will store your value.
Second you need save this Rectransform value of each UI element you create both horizontal and vertical:


Then in the script you put saved value to RectTransform when Screen is Horizontal or Vertical.
Here the RectTransform in Editor and value your need to change in script.

The UI_1, you need to set up AnchoMin, AnchoMaz, AnchorPosition and SizeDelta

The UI_2, cause anchor is Stretch , follow this 

you need change AnchorPosition Y, SizeDelta Y, offsetMin X, offsetMax x And AnchorMin, AnchorMax

Now assign value to script and testing.

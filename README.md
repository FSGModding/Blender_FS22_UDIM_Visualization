# Giants vehicleShader.xml UDIM Visualization

Mostly simple to use material that will help visualize the Giants UDIM system in your working file

## Requirements

At least blender 3.0, probably 3.1

## Installing

Download the blend file and the folder of images.  Put the folder of images the same place as the blend file.

## To Use

1.) Append the material from the blend file, "UDIMTileVisualization"
2.) Set the material of your working piece to "UDIMTileVisualization"

### NOTES

If you have only one mesh, be sure to give your original material a fake user so you don't lose it.

You can export with this (community exporter), but it does not use the default shader, so you'll have to set all of your vmask/normal/tangents by hand in GE.

## Options

* __UDIM Tile Scale Factor__ Controls how big the little numbers are.  Inverted, so, larger number == smaller.

* __Checker Scale__ Controls how big the checks in the check map are.  Inverted as well.

* __Color Brightness__ Controls how bright the colors are, 0 = black, 1 = really bright.

* __Extra Background File__ If blender is being difficult about letting you select your preferred background image in the UV editor, you can link it to the node.  It's used, so blender should be happier, but it's never shown in the rendering.

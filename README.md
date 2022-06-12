# Giants vehicleShader.xml UDIM Visualization

Mostly simple to use material that will help visualize the Giants UDIM system in your working file

## Requirements

At least blender 2.93? (maybe earlier, not gonna test), although it might whine that it was made in 3.x

## Installing

Download the blend file.  Requires no external files, the "colorMap" should already be in the blend file.

## To Use - Vehicle Shader

1.) Append the material from the blend file, "GiantsVehicleShader"
2.) Set the material of your working piece to "GiantsVehicleShader"

## To Use - Building Shader

1.) Append the material from the blend file, "GiantsBuildingShader"
2.) Set the material of your working piece to "GiantsBuildingShader"

### NOTES

If you have only one mesh, be sure to give your original material a fake user so you don't lose it (if needed)

You can export with this (community exporter) - set your vmask and normal as usual (dummy files are already there)

## Options - Vehicle

* __UDIM Tile Scale Factor__ - Controls how big the little numbers are.  Inverted, so, larger number == smaller.

* __UDIM Tile Brightness Scale__ - Controls how bright the colors are, 0 = black, 1 = default, 40 = really, really bright.

* __colorMat0 - colorMat7__ - User Colors.  Note that setting them here does not set them in the exporter.  Maybe someday

## Options - Building

* __UVTile Scale__ - Controls how much the UV Tile background is scaled - Large number == smaller boxes

* __UVTile Gamma__ - Controls the brightness of the background grey in the UVTiles

* __Non colorScale Background__ - A color or image for when the UV is *not* in the colorScale space.

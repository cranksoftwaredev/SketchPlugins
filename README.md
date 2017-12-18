![Crank Software](http://www.cranksoftware.com/sites/all/themes/crank-theme/images/Crank-logo.png)

# SketchPlugins

This is a plugin repository for Sketch that allows a design file to be exported so that it can be imported into [Crank Software's Storyboard Suite](http://www.cranksoftware.com/storyboard)

[![What Is Storyboard](http://img.youtube.com/vi/E0LO0FtbXvs/0.jpg)](http://www.youtube.com/watch?v=E0LO0FtbXvs)

The plugin will generate a Storyboard Engine runtime file (\*.gapp) and associated images resources such that it can be imported directly
into Storyboard Designer and then refined with interactive actions.

## Using the Storyboard Sketch Plugin

This plugin provides two additional menu items under the *Plugins* menu
- Export All Artboards to Storyboard
- Export Selected Artboards to Storyboard

Depending on the nature of your Sketch design you will either want to export the entire design (if no artboards are being used) or
you may prefer to only export a portion of the content by explicitly selecting those artboards that you want to use.

In either case you will be prompted for a directory where the export can take place.  This directory is where the plugin will
create a fixed Storyobard Engine file and create an `images` directory where generated content from the Sketch design will 
be created.

## Importing To Storyobard Designer

The output from the plugin export is a file `sketch_export.gapp` that can be imported directly into Storyboard Designer via
the *File > Import > Storyboard Embedded Engine (GAPP)*.  This will create a new model design file within Storyboard Designer 
along with all of the image assets.

For more information on working with Storyboard Designer:
 
* http://www.cranksoftware.com/video-library
* http://www.cranksoftware.com/product-documentation

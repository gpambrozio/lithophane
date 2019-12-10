# Requirements

* [imagemagick](https://imagemagick.org/script/download.php#macosx)

Run `brew install imagemagick`. If you don't have [Homebrew](https://brew.sh/), then just install it too.

* [OpenSCAD](https://www.openscad.org/downloads.html)

[Download](https://www.openscad.org/downloads.html) and install.

# Tweaking your image

The most important part is to create an image suitable to the conversion.

* Create a square image as all script rely on that.
* Convert it to grayscale
* Tweak the contrast and brightness so that you have an image with some part in white and some parts in black. The more contrast the better.
* Save as a PNG.

# Creating an STL file from an image

Just drag your image file to the `convert_to_lithophane.app` and it will do all the work. It will create a file called `lithophane.stl` and will try to open that with your default stl editor.

Now just print that!

# What if something goes wrong?

It might be some path issue. You can open the `convert_to_lithophane.app` in Automator and try to figure out what's wrong.

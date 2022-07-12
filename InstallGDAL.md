# `gdal`


# `gdal` install

Then get `gdal`:

Install the headers files first to avoid GDAL fail.

	brew install gdal --HEAD

Then

	brew install gdal

Check the install with:

	gdal-config --version

which should give e.g.

	3.5.1

If you hit problems, read what it says and respond accordingly. For OS X for example, you may need to install `xcode` command line tools if you don't already have that. N.B. That might take some time. You might also look at [this advice page](https://medium.com/@egiron/how-to-install-gdal-and-qgis-on-macos-catalina-ca690dca4f91)


	
	

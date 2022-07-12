# `gdal`

To use `gdal` in Python, you need to install the `gdal` packages on your computer. One way to do this is to use the package manager [`homebrew`](https://brew.sh). We will follow that approach here. 

# 1. Install `brew`

[Install homebrew](InstallBREW.md)

# 2. `gdal` install

Now install `gdal`:

Install the headers files first to avoid GDAL fail.

	brew install gdal --HEAD

Then

	brew install gdal

Check the install with:

	gdal-config --version

which should give e.g.

	3.5.1

If you hit problems, read what it says and respond accordingly. For OS X for example, you may need to install `xcode` command line tools if you don't already have that. N.B. That might take some time. You might also look at [this advice page](https://medium.com/@egiron/how-to-install-gdal-and-qgis-on-macos-catalina-ca690dca4f91)


# 3. other software

You might find it useful to use `brew` to install some other basic software that might be missing from your computer. One good example is `wget`, which is an alternative to `curl`:

	brew install wget
	
	

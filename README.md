Onedrive Uploader
=================

This is a simple bash script to parallelly upload files to Onedrive.

Requirements
----------

* An onedrive account (obviously)
* python-onedrive (https://github.com/mk-fg/python-onedrive)

Follow setup instructions for python-onedrive in its README. `onedrive-cli quota` should succeed if everything is setup correctly.

Usage
-----

The script can upload:
* a single file: `./uploadtoonedrive myfile.txt "/Personal Files/Collection"`
* a whole folder: `./uploadtoonedrive "~/Music/Pink Floyd" "/Music"`
* To increase/decrease number of parallel uploads (default is 10): `./uploadtoonedrive "~/Music/Pink Floyd" "/Music" 20`

See full options: `./uploadtoonedrive --help`
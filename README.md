# DroidWall

This is a clone of DroidWall, created by Rodrigo Zechin, which was released under
the GPLv3.

It looks like development has stagnated, so I will be looking at fixing a few 
minor issues that have been annoying me.

# Plans for development

* Fix logging
* Find out why kernel needs access to provide decent performance on CM10
* Suggest safe defaults
* An easier way to bulk enable/disable applications

# Notes

If you are having any problems with DroidWall enabled, you probably want to enable the following:

* "Messaging" application to access your 2G/3G network (for MMS)

* "YouTube" application (for searching) and the "Media Server" (for playback). 

* "Market"/"Play", "Media Storage, DRM Protected Content Storage, Download Manager"
  and "Calendar Sync Adapter, Google Services Framework, Contacts Sync Adapter"
  (for download) for Google Play.

* "(Kernel) - Linux kernel" in case you have slow download performance (I don't know why yet)

# Structure

## Branches

* master will eventually hold the latest release (when we release)
* develop is where all the action is

## Tags

There is a tag for each released version.

Peter Hoeg

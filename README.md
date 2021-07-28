# fileTracker

## Purpose
This script can be used to update the dataset tracker with new files in an automated way.

## Use
* User should create pa objects using the PA name as the "name" attribute and a list of filepaths to where the PA's raw data is stored.
* User should create a fileTracker object with a list containing the pa objects, a path to the tracker's location, and the name of the file itself.
* User can then access the fileTracker's methods - exportTracker is main useful method that will export a copy of the updated dataset tracker and archive the previous one.

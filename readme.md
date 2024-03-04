# OpenLP Stage View

From v0.9.11 of the official Stage Remote, older browsers cannot be used.

This is presumably needed for the remote functionality, but it also means you can't see the simple stage view screen on your old Android tablet you were using to show the singers their words.

This custom stage view reproduces the standard OpenLP stage view but works on older browsers as well.

## Installation

- Download this repository as a zip file.
- In OpenLP, go to Tools->Open Data Folder
- Go to Stages folder
- Make a subfolder called (for example) "singer"
- Unzip the zip into this folder

## Operation

To view the stage view, go to the normal OpenLP remote address, but on the end after "stage" add "/singer" (or whatever you called the folder)

So a typical link will look like 127.0.0.1:4316/stage/singer
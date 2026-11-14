# Handswipe Viewer

A browser image viewer you can page through by waving your hand in front of the camera.

Load one or more zip files of images (or a folder), and the images inside are sorted by name and shown one at a time. Hand tracking runs in the browser with MediaPipe, so a swipe in the air turns the page.

## Features

- Open zip files, folders, or zip share links (Dropbox links are converted to direct downloads)
- Hand-swipe navigation through the camera, plus screen swipes, edge taps, and arrow keys (F for full screen)
- Adjustable swipe distance, reverse direction, and wrap-around at the ends
- Optional camera preview and hand track bar
- Saved profiles that reload a set of zips, including on another device when they come from links

## Running it

Serve the folder over HTTPS or localhost (the camera needs a secure origin) and open `index.html`. JSZip and the MediaPipe hand model are bundled in the repo. On iPhone and Safari, profiles remember file names and ask you to pick the files again.

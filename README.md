# Image Processing API App

This app resizes images in folder assets/full and the outputs to folder will be in assets/thumbnails

## Technology used:
>JavaScript
>Node.js
>jasmine.js

## Files
- ImageProcessingAPI-APP
   -assets
      -full
   -spec
      -support
   -src
      -tests

## Project setup
- npm install
- npm run build
- npm run start

## To start it in develop mode:
- npm install
- npm run watch
- npm run dev

If you want to test this app you should call the endpoint /image with the GET method with these query parameters:
- name: the image name
- width: the required width to resize to (default: 200)
- height: the required height to resize to (default: 200)
- ext: which is the extension of the image (default: jpg)


## Author
Mohamed Elkenawy
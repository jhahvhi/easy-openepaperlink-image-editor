# Easy OpenEPaperLink Image Editor & Sender

I made this because I wanted a straightforward way to send my own images
to OpenEPaperLink tags, and I couldn't find a simple workflow that did
everything I needed.

Getting an image onto a tag can involve more than just resizing it. The
image needs to match the tag's resolution, use the right colour format
and encoding, and go through other conversion steps before it can be
sent. Things like colour handling and formats such as 4:4:4 can make the
process confusing if you just want to put a picture on a label.

This project brings those steps together in one browser-based editor.
Load an image, make adjustments, convert it for the target display, and
send it to an access point without having to handle every conversion
manually.

The project was built mostly with the help of AI, with the aim of making
the process easier to use and easier to improve.

## What it can do

-   Load an image from your device, drag and drop it, or paste it from
    the clipboard.
-   Resize and prepare images for supported e-paper displays.
-   Draw and edit images with tools such as a brush, shapes, and a
    colour-selection wand.
-   Add text and QR codes.
-   Work with layers.
-   Choose dithering options and supported display colours.
-   Export the result or send it to an OpenEPaperLink access point.

Available options depend on the display and the current state of the
app.

## To-do

-   [ ] Add support for more tag models, resolutions, and display sizes.
-   [ ] Add an English-language interface and a language selector.
-   [ ] Add rotation controls for text elements.
-   [ ] Add project import/export so edits, layers, and settings can be
    saved and reopened.
-   [ ] Improve error messages and troubleshooting for sending images to
    an access point.
-   [ ] Improve the preview so the target tag resolution is easier to
    judge.

## Contributing

Found a bug or have an idea? Feel free to open an issue or submit a pull
request. If you're planning a change, contributing it here first is
appreciated because it helps keep improvements in one place and makes
them useful to everyone.

You're also welcome to fork and modify the project. Please keep the
copyright and licence notices as required by the MIT License.

## Running it

Download the HTML file and open it in a modern browser. Some browser or
network restrictions may affect sending images to an access point,
depending on your setup.

## Disclaimer

This is an independent community project and is not an official
OpenEPaperLink tool unless stated otherwise. Use it at your own
discretion.

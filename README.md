# Easy OpenEPaperLink Image Editor & Sender

A lightweight, browser-based tool for preparing images for
OpenEPaperLink e-paper tags and sending them to an Access Point (AP).

The goal is to make the image preparation workflow simple: load an
image, adjust it for your tag, edit it, preview the result, and send it
to your AP.

## Features

-   Load an image from your device, drag and drop it, or paste an image.
-   Rotate and adjust the image before editing.
-   Choose the target display size.
-   Remove background areas with a connected-region magic wand.
-   Paint directly on the image with a brush.
-   Add text, shapes, and QR codes.
-   Arrange and manage editing elements.
-   Configure dithering and choose which supported colours to use,
    including black, white, red, yellow, blue, and green.
-   Export the prepared image and send it to an OpenEPaperLink AP.

## Getting started

### Run locally

1.  Download the HTML file from this repository.
2.  Open `index.html` in a modern browser.
3.  Load an image and adjust it for your target tag.
4.  Edit the image, choose your dithering and colour settings, then
    export or send it to your AP.

Some browser features and AP communication may behave differently
depending on the browser, network configuration, and Access Point
settings.

### Host with GitHub Pages

1.  Upload the editor HTML file to the root of a GitHub repository.
2.  Name the file `index.html`.
3.  Open **Settings → Pages**.
4.  Select the `main` branch and the repository root folder (`/`), then
    save.
5.  Open the URL provided by GitHub Pages.

GitHub Pages serves the editor over HTTPS, which is useful for browser
features that require a secure context. Sending to an AP on your local
network can still be affected by browser security rules and the AP's
configuration.

## Sending to your Access Point

-   Make sure your computer or phone can reach the AP on your local
    network.
-   Check that the AP IP address entered in the editor is correct.
-   If sending fails, check the browser's network/security restrictions
    and any AP-specific requirements.

The editor runs in the browser; hosting it publicly does not
automatically bypass local-network restrictions.

## TODO

-   [ ] Add an English-language interface / language selector.
-   [ ] Add rotation controls for text elements.
-   [ ] Add project export and import, preserving image edits, text,
    shapes, and settings.
-   [ ] Improve error messages and troubleshooting for AP connection and
    upload failures.
-   [ ] Add a clearer final preview at the target tag's exact
    resolution.

## Contributing and feedback

Suggestions, bug reports, and pull requests are welcome. Please include
your browser, the target tag or display size, and relevant AP details
when reporting a problem.

## Disclaimer

This is an independent community tool and is not an official
OpenEPaperLink project unless explicitly stated by the maintainers.
Check your target display's capabilities before relying on a particular
colour palette or image mode.

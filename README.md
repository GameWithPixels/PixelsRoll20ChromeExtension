# Pixels on Roll20

Proof of concept of a Chrome extension that sends Pixels dice roll results
to the Roll20 chat.

| :exclamation: :exclamation: :exclamation: This an experimental project, not an official product. :exclamation: :exclamation: :exclamation: |
|--------------------------------------------------------------------------------------------------------------------------------------------|

The scope of this extension is very limited and you should expect to encounter
issues :)

## How To Install

1. Download the content of this repository (*).
2. Open Chrome extension manager.
3. If you downloaded the contents in a zip file then unzip it.
4. Select "Load Unpacked", browse to the folder where you downloaded the extension.

## How To Use

1. Open a game on Roll20's [website](https://roll20.net/).
2. Click on the extension icon (it looks like a puzzle piece) on the right side
   of Chrome's address bar.
3. Select the "Pixels on Roll20" extension.
3. Select a Pixels die to connect to.
4. After a few seconds the die should be connected and your rolls will appear
   in the chat!

You may connect to more than one die a time.
To edit the roll formula, re-open the extension and change the text of the macro.

If you're having problems, have a look at the DevTools Console by pressing F12
and selecting the Console tab in the DevTools window.

Please open a [ticket](
    https://github.com/GameWithPixels/PixelsRoll20ChromeExtension/issues
) on GitHub if you're having any issue.

*Note:* Connections are lost upon reloading the page.

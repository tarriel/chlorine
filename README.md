# chlorine
Replay viewer for [Halite2](https://halite.io/), in JavaScript (Electron).

# Installation

You must install [Electron](https://electron.atom.io/). Once that's done, assuming you also have npm, you can do:

```
npm install
electron .
```

# Dependencies (not counting Electron itself)
* [node-zstandard](https://www.npmjs.com/package/node-zstandard)

# Usage

Open a file from the menu, or via command line with `electron . -o filename.hlt`. Drag-and-dropping a file onto the window may also work. Once a file is opened, navigate with left and right arrow keys. (Todo: autoplay.)

# Screenshot
![Chlorine Screenshot](https://raw.githubusercontent.com/fohristiwhirl/chlorine/master/screenshot.png)

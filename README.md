# qb-wm
A (very basic <sup><small>no pun intended</small></sup>) window manager, written in [QB64](https://qb64.org)

<br />

Due to QB64 restrictions, it does not currently support X/Wayland/etc. However, I do intend to make a *thing* that can interface to programs using QB64's TCP functionality, but that would be in the far future. As it stands now, it's merely a proof-of-concept, and not practical by any means.

If you want to contribute, I will happily allow it. I don't have alot of time on my hands, and this isn't exactly a high priority for me, so any contibutions will be appreciated.

---

## Usage
Simply open `wm.bas` in the [QB64 IDE](https://github.com/QB64Team/qb64/releases/), and press <kbd>F5</kbd> to compile and run!

<br />

`back.png` is the background, and `image2.jpg` is the image displayed on the "Test" window. You can change these out with whatever you want.

*Disclaimer: I do **NOT** own the rights to these images. They're simply placeholders for now.*

<br />

Controls are:

- Click and drag to move a window.
- Click a window to get it's focus.
- Right click and drag to resize.
- Space adds a new window.
- Escape removes the current focused window.

Although that's about to change with a pull request that is on it's way.

---

## Compiling
It requires using at least version 1.4 of [QB64](https://qb64.org) to compile, because `$NOPREFIX` is not available in versions earlier than that.

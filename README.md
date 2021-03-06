![small icon](https://gitlab.com/charles-m-knox/cinnamon-utils-menu/-/raw/master/doc/small_ico.png "Small icon") cinnamon-utils-menu

---

# Cinnamon Utilities Menu

[Original posting at cinnamon spices](http://cinnamon-spices.linuxmint.com/applets/view/30)

## Installation

Extract folder

```
cinnamon-utils-menu@charles-m-knox
```

to

```
~/.local/share/cinnamon/applets/
```

Open Cinnamon Settings, navigate to Applets, and find the new applet there. You may have to restart Cinnamon (`alt+F2`, then type `r` and press `enter` to restart via command line) to see it.

## Notes

> *This section is copied verbatim from [Original posting at cinnamon spices](http://cinnamon-spices.linuxmint.com/applets/view/30) - this applet is no longer available*

![Preview](https://gitlab.com/charles-m-knox/cinnamon-utils-menu/-/raw/master/doc/preview.png "Preview")

> This applet has been deprecated because of the new menus in Cinnamon 1.4. It was a good run, ladies and gentlemen. Thanks for your support

*Cinnamon Utilities Menu* - a simple clickable item that brings up a few powerful utilities that one might use on a regular basis.

You can do the following:

- Take a screenshot of any portion of the screen (click and drag)
- Launch the GNOME Terminal
- Start GNOME Looking Glass
- Launch the Cinnamon Settings window
- Reload the current theme
- Restart Cinnamon

This was inspired by kolle's restart cinnamon extension: [Link](http://cinnamon-spices.linuxmint.com/applets/view/14); based on a user's request to have a confirmation instead of it being a one-click function. I interpreted this as "more than one-click" to restart Cinnamon, and that's what this accomplishes (along with the other choices as well).

## Other issues/questions?

Leave comments!

## Authors additional comments

The menu is programmed to launch `gnome-terminal` and `gnome-screenshot -a` for the Terminal function and the screenshot function respectively. If you have a custom terminal/screenshot program, it will not be identified by this applet.

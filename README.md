ipnb-ayoshi-theme
=================

# Overview

This is an ipython notebook theme designed to keep the focus on the code and text, as well as be visually appealing. This is a work in progress, and things are bound to change. Patches and comments are welcome.

# Installation

```sh
# Create new ipython notebook profile
ipython notebook --profile=ipnb

# Replace custom.css
cd ~/.ipython/profile_ipnb/static/custom
rm custom.css
wget https://raw.githubusercontent.com/ayoshi/ipnb-ayoshi-theme/master/custom.css

# Enjoy
ipython notebook --profile=ipnb
```

# TODO
- Remove rounding from toolbar selectors
- Improve markdown rendering code when in editing mode
- Clean up and refactor CSS (it's a mess for now)
- Style tooltips

# Screenshots

## Markdown
![Alt text](/screenshots/.png?raw=true "Markdown")

## Code
![Alt text](/screenshots/2.png?raw=true "Code")


# Thanks to
Code coloring is [Solarized by Ethan Shoonover](http://ethanschoonover.com/solarized) on grey background

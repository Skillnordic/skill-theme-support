# Skill Theme

A modern theme for Moodle, built on Boost. Sold through [Moodle Marketplace](https://marketplace.moodle.com).

This repository holds the documentation, the terms of sale and the issue tracker for Skill Theme. The code is not here.

- **Report a fault or ask a question:** [Issues](https://github.com/Skillnordic/skill-theme-support/issues)
- **Terms of sale:** [TERMS.md](TERMS.md)

## Requirements

Moodle 5.1 to 5.3. Nothing else: the theme only requires Boost, which is part of Moodle. It works with PostgreSQL, MySQL and MariaDB.

## Install

1. Download the zip file from Moodle Marketplace.
2. Go to *Site administration → Plugins → Install plugins*, and upload the zip file. Or unzip it, put the folder `skill` in `theme/`, and go to *Site administration → Notifications*.
3. Choose the theme under *Site administration → Appearance → Themes*.

## Settings

*Site administration → Appearance → Themes → Skill Theme.*

**Appearance.** Choose one of six colour schemes, or *Own colours* to set the brand colour, the accent colour and the text colour yourself. Upload a logo, and a light logo for dark mode. Choose what users see the first time (follow the device, light or dark), the corners, the font and the content width.

- The logo is shown 40 px high. Use a logo without a background (PNG or SVG with a transparent background) that is not much wider than it is high.

**Login page.** The background: an animation (mountains, northern lights or embers), your own image with an image text, or a plain colour. A headline and a short text. On phones, the background is a strip above the form.

**Home page.** A welcome text under the greeting. The picture in the banner: animated shapes, still shapes, your own image, or nothing. Which cards students and teachers see (all are off until you switch them on). A card with up to four links for teachers, for example to your help pages.

**Features.** Switch off any part of the design: the top menu, the login page, the home page, the course banner, the footer, dark mode, activity colours, or the grading frame. A part that is off looks like Boost. The credit in the footer can also be switched off.

**Advanced.** Your own SCSS, before and after the theme's styles.

## Update

Download the new zip file from Moodle Marketplace and install it the same way. Your settings are kept.

## Uninstall

Choose another theme first, for example Boost. Then uninstall Skill Theme under *Site administration → Plugins → Plugins overview*.

## Good to know

- **Dark mode and older content.** Course content often has colours set by hand: dark text, a light box, a table with light borders. In dark mode, the theme measures the contrast of this text against the background it sits on, and adjusts only what is too weak (below 4.5:1). The colours keep their hue, nothing is saved, and the content looks as before in light mode. Text on top of pictures is not adjusted. If something is still hard to read, tell us on the issue tracker, or switch dark mode off under *Features*.
- **Phones.** The main pages are in a menu at the bottom of the screen. On pages with Moodle's save bar at the bottom, the menu is hidden and the menu button at the top opens the main menu.
- **Privacy.** The theme stores one preference per user (light, dark or automatic) and contacts no external service.

## Licence

Skill Theme is free software under the GNU General Public License, version 3 or later. © 2026 Skill Nordic AS.

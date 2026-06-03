# Win95 Blogger Theme

A small Blogger theme with a Windows 95 desktop look: teal background, chunky grey windows, blue title bars, desktop icons, a sidebar, and a fixed taskbar.

## Install

1. Download or clone this repo.
2. In Blogger, open the blog you want to change.
3. Go to **Theme** and download a backup of your current theme first.
4. Use the Theme menu's restore/upload option and pick `win95-blogger-theme.xml`.
5. Open **Layout** and adjust the sidebar gadgets. Profile, Archive, Labels, and HTML gadgets fit the theme best.

## Notes

- Upload only `win95-blogger-theme.xml`; the old demo HTML files are just from the original win95.css project.
- The theme uses a few icons from this repo through jsDelivr, so the blog can show the desktop icons without separately uploading image files.
- For the About desktop icon, create a Blogger page at `/p/about.html` or edit that link in the XML.
- For the Notes desktop icon, add a `notes` label to any posts you want listed there.

## Tweaking

Most of the styling lives inside the `<b:skin>` block in `win95-blogger-theme.xml`. Search for the CSS variables near the top if you want to change the desktop color, title bar, or window colors.

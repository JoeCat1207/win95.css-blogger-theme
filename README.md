# Win95 Blogger Theme

A small Blogger theme with a Windows 95 desktop look: teal background, chunky grey windows, blue title bars, desktop icons, a sidebar, and a fixed taskbar.

## Install

1. Download or clone this repo.
2. In Blogger, open the blog you want to change.
3. Go to **Theme** and download a backup of your current theme first.
4. Use the Theme menu's restore/upload option and pick `win95-blogger-theme.xml`.
5. Open **Layout** and adjust the Header, Top Menu, Sidebar, and Footer sections. Profile, Archive, Labels, Page List, and HTML gadgets fit the theme best.

If Blogger says it could not restore the theme, apply one of Blogger's built-in second-generation themes first, then try restoring this XML again. That usually clears old locked gadget conflicts.

If you installed an earlier copy and the Blog Posts gadget is missing from Layout, replace the full template HTML with the latest `win95-blogger-theme.xml`. This version seeds `Blog1` from Blogger's default Blog Posts renderer, then styles the generated post markup.

## Notes

- Upload only `win95-blogger-theme.xml`; the old demo HTML files are just from the original win95.css project.
- The theme uses a few icons from this repo through jsDelivr, so the blog can show the desktop icons without separately uploading image files.
- For the About desktop icon, create a Blogger page at `/p/about.html` or edit that link in the XML.
- For the Notes desktop icon, add a `notes` label to any posts you want listed there.
- To add a desktop wallpaper, open **Theme** > **Customize** > **Background** and choose or upload an image. The theme uses Blogger's `body.background` setting for this.

## Tweaking

Most of the styling lives inside the `<b:skin>` block in `win95-blogger-theme.xml`. The editable theme variables are near the top of that block.

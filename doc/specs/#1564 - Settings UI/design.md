---
author: Kayla Cinnamon @cinnamon-msft
created on: 2020-07-13
last updated: 2020-07-13
issue id: #1564
---

# Settings UI Design

## Abstract

This design document describes how each page of the settings UI will be laid out along with design mockups to display how the UI will appear.

## UI Design

### Overall navigation with Launch page

This is the list of the top-level navigation items that will appear on the left nav bar:

- General
    - Launch
    - Interaction
    - Rendering
- Appearance
    - Global
    - Color schemes
    - Themes*
- Profiles
    - Defaults
    - Enumerate profiles
    - Add new
- Keyboard
- Mouse*
- Command Palette*
- Marketplace*

\* Themes, mouse, command palette, and marketplace will be added once they're implemented.

![Overall navigation](./navigation-2.png)

### Profile appearance page

This page requires special design because it includes the TerminalControl window to preview appearance changes. This preview window will appear on the following pages:

- Appearance - Color Schemes
- Profiles - Appearance

![Appearance page](./appearance.png)

### TODO - Keyboard page

The keyboard page will list the enabled key bindings and provide a way for users to add and remove them. This design is currently being developed and will be added to this document once it's complete.

## Settings layout

Below is the list of all settings on their respective pages in the settings UI. The title row aligns with the navigation view on the left of the UI. Bolded headers in those columns align with top nav on the page.

| General - Launch | General - Interaction | General - Rendering | Appearance - Global | Appearance - Color Schemes | Profiles - Global | Profiles - Enumerate profiles | Profiles - Add new |
| ---------------- | --------------------- | ------------------- | ------------------- | -------------------------- | ----------------- | ----------------------------- | ------------------ |
| Default profile (dropdown) | Copy after selection is made (checkbox) | Windows resize behavior (checkbox) | Theme (radio) | Name (text box) | **General** | **General** | **General** | **General** |
| Launch on startup (checkbox) | Copy formatting (checkbox) | Screen redrawing (checkbox) | Show/Hide the title bar (checkbox) | Cursor color (color picker) | Command line (text box) | GUID (text box) | GUID (text box) |
| Launch size (radio) | Word delimeters (text box) | Software rendering (checkbox) | Show terminal title in title bar (checkbox) | Selection background (color picker) | Starting directory (text box) | Command line (text box) | Command line (text box) |
| Launch position (text box) | | | Always show tabs (checkbox) | Background (color picker) | Icon (text box) | Starting directory (text box) | Starting directory (text box) |
| Columns on first launch (number picker) | | | Tab width mode (radio) | Foreground (color picker) | Tab title (text box) | Name (text box) | Name (text box) |
| Rows on first launch (number picker) | | | Hide close all tabs popup (checkbox) | Black (color picker) | Scrollbar visibility (radio) | Icon (text box) | Icon (text box) |
| Disable dynamic profiles (checkbox) | | | | Blue (color picker) | **Appearance** | Tab title (text box) | Tab title (text box) |
| | | | | Cyan (color picker) | Font face (text box) | Scrollbar visibility (radio) | Scrollbar visibility (radio) |
| | | | | Green (color picker) | Font size (number picker) | **Appearance** | **Appearance** |
| | | | | Purple (color picker) | Font weight (text box) | Font face (text box) | Font face (text box) |
| | | | | Red (color picker) | Padding (text box) | Font size (number picker) | Font size (number picker) |
| | | | | White (color picker) | Cursor shape (radio) | Font weight (text box) | Font weight (text box) |
| | | | | Yellow (color picker) | Cursor color (color picker) | Padding (text box) | Padding (text box) |
| | | | | Bright black (color picker) | Cursor height (number picker) | Cursor shape (radio) | Cursor shape (radio) |
| | | | | Bright blue (color picker) | Color scheme (dropdown) | Cursor color (color picker) | Cursor color (color picker) |
| | | | | Bright cyan (color picker) | Foreground color (color picker) | Cursor height (number picker) | Cursor height (number picker) |
| | | | | Bright green (color picker) | Background color (color picker) | Color scheme (dropdown) | Color scheme (dropdown) |
| | | | | Bright purple (color picker) | Selection background color (color picker) | Foreground color (color picker) | Foreground color (color picker) |
| | | | | Bright red (color picker) | Enable acrylic (checkbox) | Background color (color picker) | Background color (color picker) |
| | | | | Bright white (color picker) | Acrylic opacity (number picker) | Selection background color (color picker) | Selection background color (color picker) |
| | | | | Bright yellow (color picker) | Background image (text box) | Enable acrylic (checkbox) | Enable acrylic (checkbox) |
| | | | | | Background image stretch mode (radio) | Acrylic opacity (number picker) | Acrylic opacity (number picker) |
| | | | | | Background image alignment (dropdown) | Background image (text box) | Background image (text box) |
| | | | | | Background image opacity (number picker) | Background image stretch mode (radio) | Background image stretch mode (radio) |
| | | | | | Retro terminal effects (checkbox) | Background image alignment (dropdown) | Background image alignment (dropdown) |
| | | | | | **Advanced** | Background image opacity (number picker) | Background image opacity (number picker) |
| | | | | | Hide profile from dropdown (checkbox) | Retro terminal effects (checkbox) | Retro terminal effects (checkbox) |
| | | | | | Suppress title changes (checkbox) | **Advanced** | **Advanced** |
| | | | | | Antialiasing text (radio) | Hide profile from dropdown (checkbox) | Hide profile from dropdown (checkbox) |
| | | | | | AltGr aliasing (checkbox) | Suppress title changes (checkbox) | Suppress title changes (checkbox) |
| | | | | | Scroll to input when typing (checkbox) | Antialiasing text (radio) | Antialiasing text (radio) |
| | | | | | History size (number picker) | AltGr aliasing (checkbox) | AltGr aliasing (checkbox) |
| | | | | | How the profile closes (radio) | Scroll to input when typing (checkbox) | Scroll to input when typing (checkbox) |
| | | | | | | History size (number picker) | History size (number picker) |
| | | | | | | How the profile closes (radio) | How the profile closes (radio) |

## Potential Issues

## Future considerations

## Resources
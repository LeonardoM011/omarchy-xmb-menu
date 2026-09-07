# XMB Menu for Omarchy

A reversible, user-owned clone of `omarchy.menu` with a PS3-inspired,
full-screen interface. It keeps Omarchy's menu model, providers, actions,
application launcher, and existing `SUPER + SPACE` routing.

The overlay appears on the focused display. This version deliberately does
not change the Omarchy top bar.

## Controls

- Left / Right: choose a root category
- Up / Down: choose an item
- Enter / Right: open or run
- Left / Backspace: go back inside nested menus
- Escape or `SUPER + SPACE`: close
- Type: search all menu entries and applications
- Delete: uninstall a selected application (with confirmation)

Disable or remove `patrick.menu` to return immediately to the packaged
`omarchy.menu` implementation.

The category rail uses a fixed XMB anchor: the selected category stays put
while the surrounding categories slide horizontally. Search results are
ranked across the complete menu and show their source category when useful.

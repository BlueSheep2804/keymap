# Keymap
[![](https://cf.way2muchnoise.eu/keymap.svg)](https://www.curseforge.com/minecraft/mc-mods/keymap)
[![](https://github.com/Einjerjar/keymap/actions/workflows/build.yml/badge.svg)](https://github.com/Einjerjar/keymap)

<img src="https://i.imgur.com/Ol1Tcf8.png" width="150">

### What

- A visual keymapping mod, specially helpful if you have tons of mods that add keybinds

### Why

- Why not, also, vanilla keybind screen + controlling isn't cutting it, and for some reason, searching with controlling is
slow on my machine
- ~~Why use a keybind instead of replacing the keybinds screen? idk, I find it easier to use that way, do hit me up if you prefer to have it replace the keybinds screen as a configurable feature~~ (check "How" section)

### How

- The default keybind is ```" ` "```, aka, the grave accent key, the key below the escape key, or the key along with the tilde `" ~ "`
- If you'd like to have the old Keybinding screen on the options>controls>keybinds menu, then disable `Override Keybind Screen` (access it via ModMenu)

### Required Mods

- [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api)
- [Cloth Config API](https://www.curseforge.com/minecraft/mc-mods/cloth-config)
- [ModMenu](https://www.curseforge.com/minecraft/mc-mods/modmenu) (_to access config_)

### Features

- Visualize all assigned keys
- Visualize keys with multiple assignments
- Filter by searching and/or by category
- You can also filter the keybind with its bound key by using square brackets eg; `[left button]`
- Set keybinds by either pressing a keyboard key or by clicking on the any virtual keys (_except mouse buttons, which can only be set with the virtual keys_)
- Sleek UI (_lol_)
- OCD Triggering misalignment of some panels ( _:D_ )

---

### Images?

- Status
  - ⬜ `Available`
  - 🟩 `Set`
  - 🟥 `Conflict`
  - 🟨 `Bound to selected item`
  > ![Status](./screenshots/sample-05.png)
- Assigned keybinds on hover
  > ![Assigned keybinds on hover](./screenshots/sample-06.png)
- Filter by category + search
  > ![Filter by category + search](./screenshots/sample-03.png)

---

### Latest Changes

- some fixes for more performance (?)
- show bound key to keybind on hover
- show keybind for key on hover

---

### Help I can't xx

- **Can't rebind mouse keys?**
  - Currently, rebinding mouse key requires the user to click on the `ML`, `MM`, and `MR` buttons to assign the `Left button`, `Middle Button`, and `Right Button` respectively.

---

### BUG!

- [Github Issues](https://github.com/Einjerjar/keymap/issues)

---

### TODO
- [ ] Support Malilib hotkeys
- [ ] ~~Add conflict counter in the case that a key has more than 2 keys bound to it~~ (_replaced by hover tooltips_)
- [x] Show the actions bound to the key on hover
- [x] Show the key bound to the action on hover
- [ ] Show the mod bound to a category on hover (_if that's even possible_)
- [x] Support overriding the default keybind screen

---

### Support

<a href='https://ko-fi.com/X8X831J1L' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://cdn.ko-fi.com/cdn/kofi1.png?v=2' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

---

#### Deprecation notice

Complete UI widget rewrite, everything under v1 is practically obsolete, kept just for personal reference, will prolly be removed on succeeding updates
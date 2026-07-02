# Titanwolf IMPERIAL macOS QWERTZ-GER

Custom macOS keyboard layout and Karabiner-Elements settings for the Titanwolf
IMPERIAL QWERTZ-GER keyboard.

## Files

- `layouts/Titanwolf_IMPERIAL_German_Windows_v0.3.keylayout` - macOS keyboard layout.
- `karabiner/karabiner.json` - Karabiner-Elements profile/config.

## Install Keyboard Layout

Copy the layout file into:

```text
~/Library/Keyboard Layouts/
```

Then restart macOS, open **System Settings > Keyboard > Text Input > Edit**,
and select **Titanwolf IMPERIAL German Windows v0.3**.

## Install Karabiner Config

Install Karabiner-Elements, then copy:

```text
karabiner/karabiner.json
```

to:

```text
~/.config/karabiner/karabiner.json
```

The included Karabiner config:

- swaps Control and Command globally
- maps the Windows `DEL` key to Finder's Move to Trash shortcut
- maps media keys to volume, mute, playback, rewind, and fast-forward actions
- maps app launch keys to email, file browser, calculator, Spotlight, and the
  consumer control configuration action

For this layout, Karabiner's virtual keyboard is configured with
`keyboard_type_v2` set to `ansi`. Although the physical keyboard is ISO, this
keeps the custom `.keylayout` receiving the key codes it was built for.

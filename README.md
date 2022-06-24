# serenefox
 Dark, geometric, keyboard-focused Firefox theme.

## Installation
- Download this repository

- Navigate to `about:profiles` in your Firefox browser

- Click **Open Folder** in the Root Directory section of the Default Profile

- Create a new directory named `chrome`

- Copy Serenefox's contents to your `chrome` directory.

- Set the following `about:config` values:

```
toolkit.legacyUserProfileCustomizations.stylesheets = true
svg.context-properties.content.enabled = true
layout.css.color-mix.enabled = true
layout.css.backdrop-filter.enabled = true
```

- Navigate to `about:support` and click **Clear startup cache`.

This will restart your browser. Firefox will read the new chrome folder and apply the theme's CSS.

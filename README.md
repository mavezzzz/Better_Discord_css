# BetterDiscord CSS Customization Guide

This guide explains how to install and use custom CSS in BetterDiscord to personalize Discord's appearance.

## Requirements

Before starting, make sure you have:

* Discord installed.
* BetterDiscord installed.
* Basic knowledge of editing text files.

## Step 1: Open BetterDiscord Settings

1. Launch Discord.
2. Click the **Settings** icon (⚙️).
3. Scroll down to the **BetterDiscord** section.
4. Select **Custom CSS**.

## Step 2: Add Your CSS

You can either:

### Option 1: Paste CSS Directly

1. Open **Settings → BetterDiscord → Custom CSS**.
2. Paste your CSS code into the editor.
3. Click **Update** or save the changes.

### Option 2: Use an External CSS File

1. Create a `.css` file (for example, `theme.css`).
2. Add your custom CSS code to the file.
3. Import it into BetterDiscord using:

```css
@import url("https://your-link-here/theme.css");
```

Replace the URL with the location of your CSS file.

## Step 3: Enable Live Updates

BetterDiscord automatically reloads CSS changes. Simply save your file, and Discord will update without requiring a restart.

## Example

```css
/* Change the background color */
body {
    background-color: #1e1e2e;
}

/* Change the color of usernames */
.username_c19a55 {
    color: #89b4fa;
}
```

## Troubleshooting

### CSS Changes Are Not Applied

* Verify that BetterDiscord is installed correctly.
* Ensure there are no syntax errors in your CSS.
* Disable conflicting themes or plugins.
* Restart Discord if necessary.

### Imported CSS Does Not Work

* Confirm that the URL is accessible.
* Make sure the file ends with `.css`.
* Check for errors in the imported stylesheet.

## Additional Resources

* BetterDiscord Documentation: https://docs.betterdiscord.app/
* BetterDiscord Website: https://betterdiscord.app/

## Disclaimer

BetterDiscord is a third-party modification for Discord and is not officially supported by Discord. Use it at your own discretion.


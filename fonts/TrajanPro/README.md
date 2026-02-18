# Trajan Pro Font

This directory should contain the Trajan Pro font files if licensed.

## Font Requirements

- **Primary font**: Trajan Pro (must be licensed)
- **Fallback**: Cinzel, serif (also should be hosted locally)

## Font Files Structure

If Trajan Pro is licensed, place font files here:
- `TrajanPro-Regular.woff2`
- `TrajanPro-Bold.woff2`
- `TrajanPro-BoldItalic.woff2` (if needed)

## Licensing

⚠️ **Important**: Trajan Pro is a commercial font. Ensure you have proper licensing before including it.

If Trajan Pro cannot be licensed:
1. Use the fallback font (Cinzel) which should also be hosted locally
2. Update `tailwind.config.js` to use only the fallback font
3. Update `src/index.css` to load the fallback font via `@font-face`

## Current Status

⚠️ Font files are not included. The app will fall back to system serif fonts until fonts are added.

## Adding Fonts

1. Place font files in this directory
2. Add `@font-face` declarations in `src/index.css` or a dedicated font CSS file
3. Ensure fonts are loaded before the app renders

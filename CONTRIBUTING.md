# Contributing

Thank you for wanting to improve this shortcut pack!

## How to add new shortcuts

1. Fork the repository
2. Open `ml_math_shortcuts.plist` in any text editor
3. Add your entry following this pattern:

```xml
<dict>
  <key>phrase</key>
  <string>YOUR_SYMBOL</string>
  <key>shortcut</key>
  <string>;your_shortcut</string>
</dict>
```

4. Add the new shortcut to the table in `README.md`
5. Open a pull request with a brief description of what you added

## Naming conventions

- All shortcuts start with `;` to avoid accidental triggers
- `;name` (lowercase) → symbol or lowercase output
- `;Name` (capitalised first letter) → uppercase Greek or named set
- `;keyword` → full formula or expression snippet

## Suggestions via issues

Not comfortable editing XML? Open an issue with:
- The symbol or phrase you want
- What shortcut keyword you'd suggest
- Which field it belongs to (e.g. "statistics", "transformers")

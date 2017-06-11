themes.json example :
```json
{
  "blank": {
    "src": "vendor/snowdog/theme-blank-sass",
    "dest": "pub/static/frontend/Snowdog/blank",
    "locale": ["fr_FR"],
    "ignore": [".test"]
  },
  "default": {
    "src": "app/design/frontend/Lrntlp/theme-default",
    "dest": "pub/static/frontend/Lrntlp/default",
    "locale": ["fr_FR"],
    "parent": "blank"
  }
}
```
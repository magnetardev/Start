# Start
A simple start screen for your browser. It uses [DuckDuckGo](https://duckduckgo.com) as its search engine by default. It uses vanilla JS, and [Bulma](https://bulma.io) to make it fast, but good looking.

## Adding Shortcuts
Adding shortcuts is simple. You just go into shortcuts.json and add all your favorite shortcuts there.

- "icon" is based off of [Font Awesome](https://fontawesome.com) and uses their icons only.
- "link" is pretty straightforward, just input the link.
- "terms" is an array of strings that you can easily type in the search box to redirect to the shortcut.
- "visible" is a boolean that determines wether or not the shortcut can be found below the search box.

A template can be found below.

```json
{
  "icon": "fas fa-globe-americas",
  "link":  "https://magnetar.dev",
  "terms": ["mag", "magnetar", "magnetardev"],
  "visible": true
}
```

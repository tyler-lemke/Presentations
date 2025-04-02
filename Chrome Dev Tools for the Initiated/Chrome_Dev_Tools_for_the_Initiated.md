---
marp: true
theme: uncover
class: invert
paginate: true
---

# Chrome Dev Tools for the Initiated

## Hidden Gems & Pro Tips

---

## A Little History on Dev Tools

---

## 1st Tool with Debug + Web Inspect

- Firebug Extension in 2006
- Written by NetScape Def - Joe Hewitt
- All praise Joe and Timothy Hatcher

---

## Shortcuts

_Available in `Settings > Shortcuts`_

- **File search** – `Ctrl + P`
- **Command menu** – `Ctrl + Shift + O`
- **Open console** – `Ctrl + (Backtick)`
- **Search in panel** – `Ctrl + F`
- **Global search** – `Ctrl + Shift + F`

---

## The Console

### Console Settings Overview

---

### Console Filtering

#### [✓] Selected Context Only

- Enable via `Settings > Console` or the gear icon
- Filters out errors from:
  - 3rd-party scripts (e.g., Chrome extensions)
  - Iframed pages

---

### Other Filtering Tips

- **Sidebar filter (preferred):**  
  Use _"User messages"_ to view only JS messages (not browser logs)
- **Log type filter:**
  - Pros - Filters entire types of messages until changed
  - Cons - I always forget to change it until mass confusion has kicked in

---

### Console Utilities & Shortcuts

- `$_` — Last evaluated expression
- `$(selector)` — jQuery-style selector
- `clear()`
- `copy(object)`

---

### Useful Console Preferences

_Settings > Preferences > Console_

- Hide network messages
- Show timestamps
- Autocomplete suggestion on Enter
- Preserve log on navigation
- Enable custom formatters

---

### Handy Console Commands

- `console.table()`
- `console.group()`, `console.groupEnd()`
- `console.time()`, `console.timeEnd()`

---

## Network Settings

_Settings > Preferences > Network_

- Show User Agent Shadow DOM
- Disable cache while DevTools is open
- Color-code resource types
- Group network logs by frame

---

## Persistence

_Settings > Preferences > Persistence_

- **Enable Local Overrides**
  - [Guide](https://senuravihanjayadeva.medium.com/local-overrides-in-chrome-devtools-f4a148de30c2)

---

## Experimental Features

### (Caution - may cause issues)

_Settings > Experimental Features_

- Authored/Deployed Trees
- IgnoreList (hide known 3rd-party scripts)
- Highlight DOM violations in Elements panel
- Report contrast issues via Issues panel
- New font editor in Styles tab
- View full accessibility tree

---

## Layers Panel

- Inspect `z-index` stacking contexts and layers

---

## References Part 1

- https://developer.chrome.com/docs/devtools/tips
- https://devtoolstips.org/tips/en/inspect-user-agent-dom/
- https://senuravihanjayadeva.medium.com/local-overrides-in-chrome-devtools-f4a148de30c2

---

## References Part 2

- https://developer.chrome.com/docs/devtools/shortcuts/?utm_source=devtools
- https://developer.chrome.com/blog/devtools-tips-13?hl=en
- https://developer.chrome.com/docs/devtools/console
- https://devtoolstips.org/tips/en/custom-object-formatters/

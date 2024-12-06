---
id: obasidian-nvim-tips
aliases:
  - obasidian-nvim-tips
tags:
  - obsidian
  - nvim
  - templates
  - install
  - configuration
---

# obasidian-nvim-tips

Para el reconocimientos de los templates de Obsidan el arbol de directoios debe ser el siguiente:

```bash
~/Documents/
├── Notes
│   ├── dailies
│   │   └── 2024-12-05.md
│   └── limbo
└── Templates
    └── daily-note_template.md

```

Y la configuracion del plugin como la de a continuacion

```lua
  opts = {
    workspaces = {
      {
        name = "Notes",
        path = "~/Documents/Notes/",
      },
    },
    templates = {
      folder = "Templates",
      date_format = "%Y-%m-%d",
      time_format = "%H:%M",
    },
```

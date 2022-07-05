# Riyad's VsCode editor Setup

## Common Settings accross all project 

```json
{
  //VsCode Related Settings
  "window.titleBarStyle": "custom",
  "workbench.iconTheme": "file-icons",
  "workbench.colorTheme": "Vitesse Light",
  "workbench.productIconTheme": "icons-carbon",
  "workbench.preferredDarkColorTheme": "Vitesse Dark",
  "workbench.preferredLightColorTheme": "Vitesse Light",
  "workbench.tree.indent": 10,
  "workbench.list.smoothScrolling": true,
  "workbench.editor.limit.enabled": true,
  "workbench.editor.limit.value": 5,
  "workbench.editor.highlightModifiedTabs": true,
  "editor.minimap.enabled": false,
  "editor.cursorSmoothCaretAnimation": true,
  "editor.glyphMargin": true,
  "editor.guides.bracketPairs": "active",
  "extensions.autoUpdate": "onlyEnabledExtensions",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.fontWeight": "300",
  "terminal.integrated.defaultProfile.linux": "zsh",
  "terminal.integrated.fontSize": 14,

  //Font Related Setting
  "editor.fontFamily": "Fira Code, monospace",
  "editor.fontSize": 15,
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "editor.fontLigatures": true,

  //Search
  "search.exclude": {
    "**/.git": true,
    "**/.github": true,
    "**/.nuxt": true,
    "**/.output": true,
    "**/.pnpm": true,
    "**/.vscode": true,
    "**/.yarn": true,
    "**/bower_components": true,
    "**/dist/**": true,
    "**/logs": true,
    "**/node_modules": true,
    "**/out/**": true,
    "**/package-lock.json": true,
    "**/pnpm-lock.yaml": true,
    "**/tmp": true,
    "**/yarn.lock": true
  },

  //All Common Extension Settings are here

  //Cspell
  "cSpell.allowCompoundWords": true,
  "cSpell.language": "en,en-US",

  //Emmet
  "emmet.showSuggestionsAsSnippets": true,
  "emmet.triggerExpansionOnTab": false,

  //ErrorLens
  "errorLens.enabledDiagnosticLevels": ["warning", "error"],
  "errorLens.excludeBySource": ["cSpell", "eslint"],

  //IconFy
  "iconify.annotations": true,
  "iconify.inplace": true,

  //SVG
  "svg.preview.mode": "svg"
}
```

## Common Extension accross all projects

```json
{
  "recommendations": [
    "antfu.iconify",
    "antfu.unocss",
    "antfu.where-am-i",

    "antfu.icons-carbon",
    "antfu.theme-vitesse",
    "file-icons.file-icons",
    "sainnhe.gruvbox-material",

    "dbaeumer.vscode-eslint",
    "Vue.volar",
    "usernamehw.errorlens",
    "streetsidesoftware.code-spell-checker",
    "formulahendry.auto-rename-tag",
    "ritwickdey.liveserver",
    "vue.vscode-typescript-vue-plugin",
    "esbenp.prettier-vscode",
  ]
}

```
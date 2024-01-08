// Required Plugin: https://marketplace.visualstudio.com/items?itemName=drcika.apc-extension

{
  "[typescript]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  },
  "[prisma]": {
      "editor.formatOnSave": true
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },
  "workbench.statusBar.visible": false,
  "editor.hideCursorInOverviewRuler": true,
  "editor.minimap.enabled": false,
  "editor.glyphMargin": false,
  "editor.folding": false,
  "window.titleBarStyle": "native",
  "apc.electron": {
    "frame": false,
    "titleBarStyle": "hidden",
    "trafficLightPosition": {
      "x": 11,
      "y": 10,
    },
  },
  "apc.header": {
    "height": 36
  },
  "editor.tabSize": 2,
  "editor.cursorStyle": "block",
  // Remove unnecessary controls from primary bar and tabs list
  "apc.stylesheet": {
    ".title-label > h2": "display: none", // Remove primary side bar title
    ".title-actions": "display: none", // Remove primary side bar action icons
    ".editor-actions": "display: none", // Remove editor action icons
    ".nosidebar .inline-tabs-placeholder": "width: 75px", // Align tabs to not overlap window controls when primary bar is hidden
    ".title-label": "display: none !important",
    ".composite.title": "display: block !important",
    ".monaco-workbench .part.sidebar .title-actions .actions-container": "justify-content: space-evenly !important"
  },
  "workbench.colorTheme": "Vesper ++",
  "workbench.activityBar.location": "hidden",
  "workbench.sideBar.location": "right",
  "material-icon-theme.languages.associations": {
    "dotenv": "tune"
  },
  "workbench.iconTheme": "material-icon-theme",
  "files.associations": {
    ".sequelizerc": "javascript",
    ".stylelintrc": "json",
    "*.tsx": "typescriptreact",
    ".env.*": "dotenv",
    ".prettierrc": "json",
  },
  "material-icon-theme.activeIconPack": "nest",
  "material-icon-theme.files.associations": {
    "*.repository.ts": "nest-decorator",
    "*.dto.ts": "nest"
  },
  "material-icon-theme.folders.associations": {
    "adapters": "contract",
    "grpc": "pipe",
    "kube": "kubernetes",
    "main": "lib",
    "websockets": "pipe",
    "implementations": "core",
    "protos": "pipe",
    "entities": "class",
    "kafka": "pipe",
    "use-cases": "functions",
    "migrations": "tools",
    "schemas": "class",
    "useCases": "functions",
    "eslint-config": "tools",
    "typeorm": "database",
    "_shared": "shared",
    "mappers": "meta",
    "fakes": "mock",
    "modules": "components",
    "subscribers": "messages",
    "domain": "class",
    "protocols": "contract",
    "infra": "app",
    "view-models": "views",
    "presentation": "template",
    "dtos": "typescript",
    "http": "container",
    "providers": "include",
    "factories": "class",
    "repositories": "mappings",
  },
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  }
}

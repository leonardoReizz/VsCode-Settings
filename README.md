# VsCode-Settings
Extensions: 
https://marketplace.visualstudio.com/items?itemName=miguelsolorio.fluent-icons

Visual Studio Code Settings


```
{
    "window.titleBarStyle": "custom",
    "workbench.activityBar.location": "top",
    "workbench.colorTheme": "Palenight (Mild Contrast)",
    "[typescript]": {
        "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
    },
    "[prisma]": {
        "editor.formatOnSave": true
    },
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": "explicit"
    },
    "explorer.compactFolders": false,
    "editor.accessibilitySupport": "off",
    "explorer.confirmDragAndDrop": false,
    "editor.semanticHighlighting.enabled": false,
    "breadcrumbs.enabled": true,
    "editor.tabSize": 2,
    "security.workspace.trust.untrustedFiles": "newWindow",
    "files.exclude": {
      "**\/CVS": true,
      "**\/.DS_Store": true,
      "**\/.hg": true,
      "**\/.svn": true,
      "**\/.git": true,
      // "node_modules": true
    },
    "editor.fontLigatures": true,
    "material-icon-theme.files.associations": {
      "tsconfig.json": "tune",
      "*.webpack.js": "webpack",
      "*.proto": "3d",
      "ormconfig.json": "database"
    },
    "material-icon-theme.languages.associations": {
      "dotenv": "tune"
    },
    "files.associations": {
      ".sequelizerc": "javascript",
      ".stylelintrc": "json",
      "*.tsx": "typescriptreact",
      ".env.*": "dotenv",
      ".prettierrc": "json"
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
      "repositories": "mappings"
    },
    "[jsonc]": {
      "editor.defaultFormatter": "vscode.json-language-features"
    },
    "workbench.iconTheme": "material-icon-theme",
    "editor.cursorStyle": "block",
}
```

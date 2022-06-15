---
title: Enable automatic import sorting and importing in VS Code with jsconfig.json
layout: post
date: "2022-06-16 12:00:00 +1100"
categories: vscode productivity
---

- `{
  "compilerOptions": {
    "target": "ES6",
    "jsx": "preserve",
    "baseUrl": "./src",
    "checkJs": true
  },
  "exclude": ["node_modules", "**/node_modules/*"]
}`
- during autocompletion select a cube icon with the component name and it will be imported automatically.
- [Documentation](https://code.visualstudio.com/docs/languages/jsconfig)

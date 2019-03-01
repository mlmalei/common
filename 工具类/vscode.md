[VSCode 下载地址](https://code.visualstudio.com/)

### 常用的一些插件
  - Babel ES6/ES7
  - Babelrc
  - ESLint
  - TSLint
  - prettier
  - GitLens
  - Git History
  - Git Blame
  - HTML Snippets
  - React/Redux/react-router Snippets
  - vscode-icons
  - vscode-styled-components
  - vscode-styled-jsx
  - vscode-proto3
  - stylelint
  - weex

### vscode 用户设置
```javascript
// 将设置放入此文件中以覆盖默认设置
{
  // flow typed
  "flow.enabled": false,

  //-------- TSLint configuration --------
  "tslint.exclude": [
    "typings",
    "**/*.js"
  ],
  //-------- 编辑器配置 --------
  "editor.fontFamily": "Monaco",
  "editor.fontWeight": "bold",
  "editor.lineHeight": 20,
  "editor.renderWhitespace": "all",
  "editor.tabSize": 2,
  "editor.rulers": [80, 120],

  "files.insertFinalNewline": true,
  "files.trimTrailingWhitespace": true,
  "editor.wordWrap": "on",
  "workbench.iconTheme": "vscode-icons",
  "window.zoomLevel": 0,
  "vsicons.projectDetection.autoReload": true,
  "typescript.check.tscVersion": false,
  "workbench.sideBar.location": "left",
  "editor.minimap.enabled": false,
  "extensions.ignoreRecommendations": false,
  "git.confirmSync": false,
  "vsicons.dontShowNewVersionMessage": true,
  "git.autofetch": true,
  "gitlens.advanced.messages": {
    "suppressShowKeyBindingsNotice": true
  },
  "gitlens.historyExplorer.enabled": true,
  "gitlens.views.fileHistory.enabled": true,
  "gitlens.views.lineHistory.enabled": true
}

```

### Lighthouse 审查网络应用
``` javascript
  npm install -g lighthouse
  // 针对一个页面运行 Lighthouse 审查
  lighthouse https://airhorner.com/
```

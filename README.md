# vue_code_lint_temp

一个基于Vue.js应用的代码扫描配置模板, 该模板作为配置中心, 统一通过脚手架命令下发到项目中, 统一管理配置规范。

- 完整的代码自动扫描流程, 保障代码质量
  - eslint
  - stylelint
  - prettier
  - commitlint
  - 建议统一使用编辑器VSCode, 并自行配置辅助插件如eslint, stylelint, prettiter等。

  ### VSCode统一设置（settings.json）

```
 "eslint.autoFixOnSave": true,
   "eslint.validate": [
    "javascript",
    "javascriptreact",
    {
      "language": "html",
      "autoFix": true
    },
    {
      "language": "vue",
      "autoFix": true
    }
   ],
   "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.fixAll.stylelint": true
   }

```
  


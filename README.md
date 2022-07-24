# Youth-Low-Code-Platform
## ✨ Features

## :rocket: Technologies
- 框架：React 18 + Typescript + sass + acro ui
- 代码规范：ESlint + prettier + stylelint + husky + lint-staged
- 包管理：pnpm
## 📦 Quick start
本项目使用 pnpm 作为包管理工具，需要先全局安装 pnpm:
```bash
npm install -g pnpm
```
```bash
# Install dependencies.
pnpm install
# Run project in dev.
pnpm start
```
## :white_check_mark: Commit standards
使用Husky + lint-staged 的 Git 提交工作流集成

commit由两部分组成, 结构如下：
```
// type 指提交的类型
// subject 指提交的摘要信息
commit格式如下
<type>: <subject>
```
常用的 type 值包括如下:
- feat: 添加新功能
- fix: 修复 Bug
- chore: 一些不影响功能的更改
- docs: 专指文档的修改
- perf: 性能方面的优化
- refactor: 代码重构
- test: 添加一些测试代码等等
- build: 构建相关

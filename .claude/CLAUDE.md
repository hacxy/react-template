# 项目规范

## 文件与目录命名

| 分类 | 规则 | 示例 |
|------|------|------|
| 目录名 | kebab-case | `pages/`, `layouts/`, `store/`, `router/` |
| React 组件文件 | PascalCase | `Home.tsx`, `RootLayout.tsx`, `NotFound.tsx` |
| 组件配套 CSS | PascalCase，与组件同名 | `RootLayout.css` |
| 非组件 TS/TSX 文件 | camelCase | `main.tsx`, `counter.ts`, `index.ts` |
| 全局 CSS | camelCase | `index.css`, `App.css` |
| 静态资源 | kebab-case | `hero.png`, `react.svg` |
| E2E 测试文件 | kebab-case + `.spec.ts` | `app.spec.ts` |
| 测试辅助文件 | camelCase | `fixtures.ts`, `globals.d.ts` |

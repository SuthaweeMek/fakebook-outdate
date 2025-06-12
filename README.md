# fakebook-outdate

1. git clone https://github.com/paiboonpa/fakebook-outdate.git
2. npm i
3. npm audit

## Key Library Versions
- **Ant Design (antd)**: Upgraded from v3.25.1 to v5.12.5.
  - This upgrade involved addressing breaking changes primarily related to icon usage, Form APIs (using `@ant-design/compatible` for older forms), and the adoption of CSS-in-JS by antd v5 (replacing LESS file imports with a CSS reset via `antd/dist/reset.css`). Codemods (`@ant-design/codemod-v4` and `@ant-design/codemod-v5`) were utilized.

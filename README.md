# CRM 后台迁移实战

CRM 客户与销售运营台 Vue 3 项目迁移实战。

本示例是标准 `vue-ts` 风格工程，，用于验证常规 Vite + Vue3 + Vue Router 项目的闭环转换。

简体中文 | [English](./README.en.md)

## 开始使用

### 注意事项

- 若 `vureact(watch)` 监听任务未运行，请在项目根目录执行 `pnpm vr:watch`，否则 Vue 端的修改将无法同步至 React 应用。

- 在 CodeSandbox 在线环境中，通常无需手动执行以下步骤。若预览页面未能正常启动，请进入 `.vureact/react-app/` 目录并运行 `npm run dev` 即可。

### Step 1: 运行 VuReact 构建

- 安装依赖

```bash
npm install
```

- 执行编译

```bash
# 方式一：vureact 全量编译
npm run vr:build

# 方式二：vureact 增量编译（监听模式）
npm run vr:watch
```

### Step 2: 运行 React App

- 进入工作区构建产物目录

```bash
cd .vureact/react-app/
```

- 安装依赖

```bash
npm install
```

- 启动 Vite dev 服务，并访问如 <http://localhost:5173>

```bash
npm run dev
```

## 官方教程

<https://www.vureact.top/guide/crm-admin-backend.html>

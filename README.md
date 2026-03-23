# CRM Backend Migration Practice

A hands-on practice for migrating the CRM Customer and Sales Operations Dashboard Vue 3 project.

This example is a standard `vue-ts` style project, designed to verify the closed-loop conversion of a typical Vite + Vue3 + Vue Router project.

English | [简体中文](./README.zh.md)

## Getting Started

Note: In the CodeSandbox online environment, the following steps are usually not required. If you find that the preview page does not start properly, simply navigate to the `.vureact/react-app/` directory and run `npm run dev`.

### Step 1: Run VuReact Build

- Install Dependencies

```bash
npm install
```

- Execute Compilation

```bash
# Method 1: VuReact full compilation
npm run vr:build

# Method 2: VuReact incremental compilation (watch mode)
npm run vr:watch
```

### Step 2: Run React App

- Navigate to the workspace build output directory

```bash
cd .vureact/react-app/
```

- Install Dependencies

```bash
npm install
```

- Start the Vite dev server and visit, for example, <http://localhost:5173>

```bash
npm run dev
```

## Official Tutorial

<https://www.vureact.top/en/guide/crm-admin-backend.html>

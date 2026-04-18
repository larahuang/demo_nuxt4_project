# Nuxt Starter Template Nuxt 啟動模板

[![Nuxt UI](https://img.shields.io/badge/Made%20with-Nuxt%20UI-00DC82?logo=nuxt&labelColor=020420)](https://ui.nuxt.com)

Use this template to get started with [Nuxt UI](https://ui.nuxt.com) quickly.

- [Live demo](https://starter-template.nuxt.dev/)
- [Documentation](https://ui.nuxt.com/docs/getting-started/installation/nuxt)

<a href="https://starter-template.nuxt.dev/" target="_blank">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://ui.nuxt.com/assets/templates/nuxt/starter-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="https://ui.nuxt.com/assets/templates/nuxt/starter-light.png">
    <img alt="Nuxt Starter Template" src="https://ui.nuxt.com/assets/templates/nuxt/starter-light.png" width="830" height="466">
  </picture>
</a>

> Vue 的初始模板位於 The starter template for Vue is on https://github.com/nuxt-ui-templates/starter-vue.

## Quick Start

```bash [Terminal]
npm create nuxt@latest -- -t ui
```

## Deploy your own 部署您自己的模板

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-name=starter&repository-url=https%3A%2F%2Fgithub.com%2Fnuxt-ui-templates%2Fstarter&demo-image=https%3A%2F%2Fui.nuxt.com%2Fassets%2Ftemplates%2Fnuxt%2Fstarter-dark.png&demo-url=https%3A%2F%2Fstarter-template.nuxt.dev%2F&demo-title=Nuxt%20Starter%20Template&demo-description=A%20minimal%20template%20to%20get%20started%20with%20Nuxt%20UI.)

### Step1  建立project-name
<a href="https://nuxt.com/docs/4.x/getting-started/installation" target="_blank">參考官網</a>

```
npm create nuxt@latest <project-name>

> npx
> create-nuxt demo_nuxt_project


        .d$b.
       i$$A$$L  .d$b
     .$$F` `$$L.$$A$$.
    j$$'    `4$$:` `$$.
   j$$'     .4$:    `$$.
  j$$`     .$$:      `4$L
 :$$:____.d$$:  _____.:$$:
 `4$$$$$$$$P` .i$$$$$$$$P`

┌  Welcome to Nuxt!
│
◇  Templates loaded
│
◆  Which template would you like to use?
│  ○ content – Content-driven website
│  ○ minimal – Minimal setup for Nuxt 4
│  ○ module – Nuxt module
│  ● ui – App using Nuxt UI
```
### 架構
```
2025_liff_in_nuxt/
├── .nuxt/                 # Nuxt開發中，根據目錄結構生成。
├── .output/               # Nuxt build 後的輸出目錄（用於部署）
├── .env                   # 環境配置檔
├── assets/                # 靜態資源
├── components/            # Vue 元件
├── composables/           # 邏輯函式
├── content/               # 資料檔案
├── layouts/               # 自訂佈局
├── middleware/            # 中介層邏輯
├── pages/                 # 頁面檔案
├── plugins/               # 套件
├── public/                # 靜態公開檔案
├── server/                # 放後端邏輯
│   └── api/
│       └── order.js       # 對應 /api/order
├── app.vue                # Nuxt 應用入口點
├── nuxt.config.ts         # Nuxt 配置設定檔（支援 TypeScript）
├── package.json           # 套件與指令設定
├── tsconfig.json          # TypeScript 設定
└── README.md              # 專案說明
```

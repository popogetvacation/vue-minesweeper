<p align='center'>
  <img src='https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fimg1.3png.com%2Fb49c1da9be2467c8bcd2bf0bb6f0f3a47b5d.png&refer=http%3A%2F%2Fimg1.3png.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1650601295&t=cd5c50c73999b2012606adaeb15ed52b' alt='Vitesse - Opinionated Vite Starter Template' width='600'/>
</p>

<h6 align='center'>
<a href="http://120.79.209.247:7777/">在线 Demo</a>
</h6>

<h5 align='center'>
<b>轻量版的 <a href="https://github.com/antfu/vitesse">Vitesse</a></b>
</h5>

<br>

<p align='center'>
<a href="https://github.com/antfu/vitesse-lite/blob/main/README.md">English</a> | <b>简体中文</b>
</p>

<br>

## 特性

- ⚡️ [Vue 3](https://github.com/vuejs/vue-next), [Vite 2](https://github.com/vitejs/vite), [pnpm](https://pnpm.js.org/), [ESBuild](https://github.com/evanw/esbuild) - 就是快！

- 🗂 [基于文件的路由](./src/pages)

- 📦 [组件自动化加载](./src/components)

- 🎨 [UnoCSS](https://github.com/unocss/unocss) - 高性能且极具灵活性的即时原子化 CSS 引擎

- 😃 [各种图标集为你所用](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

- 🔥 使用 [新的 `<script setup>` 语法](https://github.com/vuejs/rfcs/pull/227)

- ✅ 使用 [Vitest](http://vitest.dev/) 进行单元和组件测试

- 🦾 TypeScript, 当然

- ☁️ 零配置部署 Netlify

<br>

完整特性,请查看 [Vitesse](https://github.com/antfu/vitesse)

## 从 [Vitesse](https://github.com/antfu/vitesse) 中删除了以下特性

- ~~i18n~~
- ~~Layouts~~
- ~~SSG~~
- ~~PWA~~
- ~~Markdown~~

## 预配置

### UI 框架

- [UnoCSS](https://github.com/antfu/unocss) - 高性能且极具灵活性的即时原子化 CSS 引擎

### Icons

- [Iconify](https://iconify.design) - 使用任意的图标集，浏览：[🔍Icônes](https://icones.netlify.app/)
- [UnoCSS 的纯 CSS 图标方案](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

### 插件

- [Vue Router](https://github.com/vuejs/vue-router)
  - [`vite-plugin-pages`](https://github.com/hannoeru/vite-plugin-pages) - 以文件系统为基础的路由
- [`unplugin-auto-import`](https://github.com/antfu/unplugin-auto-import) - 直接使用 Composition API 等，无需导入
- [`unplugin-vue-components`](https://github.com/antfu/unplugin-vue-components) - 自动加载组件
- [VueUse](https://github.com/antfu/vueuse) - 实用的 Composition API 工具合集

## 现在可以试试!

### GitHub 模板

[使用这个模板创建仓库](https://github.com/antfu/vitesse-lite/generate).

### 克隆到本地

如果您更喜欢使用更干净的 git 历史记录手动执行此操作

```bash
npx degit antfu/vitesse-lite my-vitesse-app
cd my-vitesse-app
pnpm i # 如果你没装过 pnpm, 可以先运行: npm install -g pnpm
```

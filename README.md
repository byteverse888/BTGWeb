# AIGC_Web_APP
巴特AI星球是一个聚焦于AI的创新社区，以AI为生产工具、数据为生产资料，结合WEB3新型生产关系，打造分布式AI算力网络，共创共建AI+Web3共享社区，构建可持续进化的AI数字神兽。社区的愿景是推动AI技术的普及和普惠，让更多人享受到AI带来的便利和价值，促进AI技术的可持续发展，享受AI带来的颠覆性价值红利！

本项目是AIGC应用Web端，基于Vue 3 in Vite 构建，使用VUE3+vite+Vue Router+Pinia+axios+typerscript+npm版本控制。
Vue3的web端组件库：http://element-plus.org/zh-CN/guide/design.html

## 推荐的IDE Setup
推荐使用的 IDE 是 VSCode，配合 Vue - Official 扩展 (之前是 Volar)


## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## 安装nodejs 20.12：
#installs NVM (Node Version Manager)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
nvm install 20
node -v # should print `v20.12.2`
npm -v # should print `10.5.0`

#设置国内镜像源：
npm config set registry https://registry.npmmirror.com

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

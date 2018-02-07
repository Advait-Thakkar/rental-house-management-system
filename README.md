# yarn 快速入门

## 安装

### windows 环境
1. 下载并安装 Node.js
2. 下载并安装 *.msi

### macOS
Homebrew 包管理器

```bash
brew install yarn
```
如果您使用 nvm 或类似的东西，您应该排除安装 Node.js 以便使用 nvm 的 Node.js 版本。

```bash
brew install yarn --without-node
```
MacPorts

``` bash
sudo port install yarn
```
## 使用

### 初始化项目
```bash
yarn init
```

### 添加依赖包
```bash
yarn add [package]
yarn add [package]@[version]
yarn add [package]@[tag]
```

### 将依赖项添加到不同依赖项类别
分别添加到 devDependencies、peerDependencies 和 optionalDependencies：

```bash
yarn add [package] --dev
yarn add [package] --peer
yarn add [package] --optional
```

### 升级依赖包
```bash
yarn upgrade [package]
yarn upgrade [package]@[version]
yarn upgrade [package]@[tag
```


### 移除依赖包
```bash
yarn remove [package
```

### 安装项目的全部依赖
```
yarn or yarn install
```
或者
```
 yarn install
```

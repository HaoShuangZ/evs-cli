[English](./README.EN.md) | 简体中文

<p align="center"><img width="100" src="https://vuejs.org/images/logo.png"></p>

<h2 align="center">evs-cli（一个简单的前端CLI工具）</h2>
<p align="center"><b>基于Node搭建生成个人前端脚手架（vue）</b></p>

# 目录

- [特性](#特性)
- [快速入门](#快速入门)
  - [安装](#安装)
  - [用法](#用法)
- [贡献者们](#贡献者们)
- [维护者](#维护者)
- [License](#license)

### 特性

- 简单易用
- 支持自定义模板增删

## 快速入门

### 安装

```bash
$ npm i evs-cli -g               # install cli
$ omi init my-app     # init project, you can also exec 'omi init' in an empty folder
$ cd my-app           # please ignore this command if you executed 'omi init' in an empty folder
$ evs init [templateName] [yourProjectName]
```

安装说明:

默认的脚手架模板名称是vue-admin
> evs init vue-admin [yourProjectName]

### 新增模板用法

```bash
evs add
# 选择模板和模板地址（github地址）
```

- 注意：模板地址为git仓库名称 默认拉取master分支
 如果想指定分支 请使用 **owner/name#my-branch**的方式

### 删除模板用法

```bash
evs delete
# 选择模板
```

### 查看所有模板用法

```bash
evs list
```

### 初始化项目脚手架用法

```bash
evs init 或者 evs init [templateName] [yourProjectName]
```


## 贡献者们
- HaoShuangZ

## 维护者

- [HaoShuangZ](https://github.com/HaoShuangZ)

## License

- [MIT](https://opensource.org/licenses/MIT)

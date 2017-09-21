# doctoc-tool
https://github.com/thlorenz/doctoc#installation

## 安装：
```
npm install -g doctoc
```

## 用法：
### 将目录和子目录中的所有文件添加到
> 进入包含本地git项目的目录，并键入：

```
doctoc .
```
> 这将更新当前目录及其子目录中的所有 MD 文件。

### 更新现有的 doctoc TOC
> 如果已经用 doctoc 插入了 TOC，运行命令后会自动更新。

### 给特定的的单个文件添加 TOC
```
doctoc /path/to/file
//比如：
doctoc README.md
doctoc CONTRIBUTING.md LICENSE.md
```

。。。
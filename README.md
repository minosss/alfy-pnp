# alfy-pnp

> [alfy](https://github.com/sindresorhus/alfy): Create Alfred workflows with ease

alfy 可以很方便创建 Alfred 的 workflow。不过 node 有个问题就是每个项目都有 node_modules 目录，严重占用了硬盘空间。所以使用 Yarn 的 PnP 来共享 node_modules 来减少每个项目体积。

## Usage

使用方法跟 [alfy](https://github.com/sindresorhus/alfy#usage) 的一样，不过运行脚本使用 pnp

```
NODE_OPTIONS="--require ./.pnp.js" ./run-node index.js "$1"
```

运行 `yarn install` 会生成 `.pnp.js` 文件

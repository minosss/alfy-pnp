# alfy-pnp

> [alfy](https://github.com/sindresorhus/alfy): Create Alfred workflows with ease

alfy 可以很方便创建 Alfred 的 workflow。不过 node 有个问题就是每个项目都有 node_modules 目录，严重占用了硬盘空间。所以使用 Yarn 的 PnP 来共享 node_modules 来减少每个项目体积。

## Install

- 安装 [Alfred](https://www.alfredapp.com/)
- 购买 [Powerpack](https://www.alfredapp.com/shop/)

推荐使用 Yarn

```sh
$ yarn global add your-alfy-workflow
```

## Usage

使用方法跟 [alfy](https://github.com/sindresorhus/alfy#usage) 的一样

```
./node_modules/run-node index.js "$1"
```

## Related

- [alfy-ipip](https://github.com/minosss/alfy-ipip) - 查询 ip 信息

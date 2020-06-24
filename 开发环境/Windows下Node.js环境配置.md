## 通过 nvm 管理 nodejs 版本

### 安装 nvm-windows

- [nvm-windows](https://github.com/coreybutler/nvm-windows)

### 配置 node/npm 下载镜像

由于众所周知的原因，安装好 nvm-windows 后下载 node/npm 时很有可能会下不下来，这时候需要修改 nvm 配置文件：

```bash
# C:\Users\${用户名}\AppData\Roaming\nvm
node_mirror: https://npm.taobao.org/mirrors/node/
npm_mirror: https://npm.taobao.org/mirrors/npm/
```

## 通过 nrm 管理 npm 镜像源

- [nrm](https://github.com/Pana/nrm)

## 安装 node-gyp

- [windows-build-tools](https://github.com/felixrieseberg/windows-build-tools)
- [node-gyp](https://github.com/nodejs/node-gyp)

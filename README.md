# tnvm
Taobao Node Version Manager


## Installation
```shell
wget -qO- https://raw.githubusercontent.com/aliyun-node/tnvm/master/install.sh | bash
```
PS: 内网环境可在执行上述命令前增加执行, 内部使用wget获取文件
```
export METHOD=script
```
手动source rc文件或重新打开sh,即可启动。

如果遇到 ssl 证书问题， 尝试`wget`加上选项`--no-check-certificate`



## Usage
Support `alinode`, `node`, `iojs`, `node-profiler` version manager

Example:
 * tnvm ls alinode
 * tnvm ls-remote alinode
 * tnvm install alinode-v0.12.6
 * tnvm install node-v0.12.6
 * tnvm use alinode-v0.12.6

More:
 * refer to `tnvm help`

Note:
  * to remove, delete, or uninstall tnvm - just remove ~/.tnvm folders


## License

tnvm is released under the MIT license.

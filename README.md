# README

* 事实上, tiddlywiki.files 只管理当前文件夹下的文件(支持递归), 也是可以放在tiddlers 文件夹下的子文件夹下,注意不要放在tiddlers文件夹下的根目录下
* 注意不要重复文件名
* 此仓库主要是针对markdown文件迁移到tiddlywiki里面的演示

## File Structure

```sh
├── 📁md
│   ├── 📁tiddlers
│   │   ├──📝 first.md
│   │   ├──📝readme.md
│   │   └──📁 tiddlywiki.files
│   └── 📝tiddlywiki.info
├── 📝README.md
├──📁 tiddlers
│   ├── $__Import.tid
│   ├── $__plugins_nico_projectify.json
│   ├── $__plugins_nico_projectify.json.meta
│   ├── $__StoryList.tid
│   ├── 📝create md-to-tiddlywiki example.tid
│   ├── 📝readme.md
│   ├── 📝readme.md.meta
│   └── 📁subdir
│       ├── 📝 first-sub.md
│       ├── 📝 readme-sub.md
│       └── 📝 tiddlywiki.files
└── tiddlywiki.info
```

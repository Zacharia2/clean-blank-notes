# Logseq Plugin: *clean-empty-pages*

## 如何使用

仅注册了PageMenuItem，删除空白日志。所以可以在页标题上又单击召出菜单使用。

## 关于开发

空白页的定义：页面中的每个块children长度为0，并且这些content=""。关于“没有任何引用，且没有任何内容”中没有任何引用，可以去掉，因为当页是空白页，引用一定是写在别的页上的链接，有没有引用无所谓，信息不回丢失，到时候再创建即可。


在logseq中，ctrl+shift+i开发者模式，F5可以刷新logseq。并且可以使用`pnpm run dev`命令实时生成代码。
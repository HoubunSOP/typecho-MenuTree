# typecho-MenuTree

芳文观星台MenuTree定制版

## 使用方法

在文章某处地方加上 `<!-- index-menu -->`，程序会把这个注释替换成目录树

## 样式

.index-menu      整个目录

.index-menu-list 列表 ul

.index-menu-item 每个目录项 li

.index-menu-link 目录项连接 a

## 注意

独立模式下需要在主题模板中调用：$this->treeMenu();

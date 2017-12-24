# 我如何完成这个项目

测试用例在feedreader.js里面，测试包括：

1. 遍历 allFeeds 对象里面的所有的源来保证有链接字段而且链接不是空的。
2. 遍历 allFeeds 对象里面的所有的源来保证有名字字段而且不是空的。
3. 保证菜单元素默认是隐藏的。
4. 保证当菜单图标被点击的时候菜单会切换可见状态。
5. 保证 `loadFeed` 函数被调用而且工作正常
6. 保证当用 `loadFeed` 函数加载一个新源的时候内容会真的改变。
# 遇到问题的解决流程

1. 检查代码，重新运行
2. 开启错误提示，重新运行，如果有错误提示则根据字面意思理解并分析得到解决方案，如果不能直接得到解决方案，则利用搜索引擎
3. 在 StackOverFlow 等程序员社区上提问
4. 订阅开发组邮件列表并提问
5. 定位bug所在位置（xdebug / \(var\_dump / print\_r\) & die）
6. 也有可能是 PHP 版本问题, 可以尝试在不同的 PHP 版本下进行测试
7. 也可能是 WEB SERVER 或者别的相关组件的问题, 例如 Nginx 与 Apache 的区别
8. gdb 调试
9. 查看是否为该语言尚未解决的BUG
10. 查看内核源码与扩展源码


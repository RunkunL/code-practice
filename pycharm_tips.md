# 常用pycharm使用技巧

1.快速打印
```python
a = 15
b = 15
# a+b.pri(回车) 即可
print(a+b)
```
2. 对变量或文件快速重命名  `shift+f6`
3. 格式化代码 `ctrl+alt+l`
4. 上下移动指定内容 `alt+shift+↑/↓`
5. 同时编辑多处代码 `alt选中相应位置进行修改`
6. 多个文件切换 `ctrl+tab`
7. 多个应用切换 `alt+tab`
8. 选中多行代码 `shift+↑/↓`
9. 快速注释 `ctrl+l`
10. 扩散选中 `ctrl+w`
11. 搜索 `ctrl+f`
12. 右侧导航位置存在黄条说明此处代码可以优化
13. 标记待做事项（右侧导航位置蓝条）
```python
def fun(a,b):
    # todo 功能有待完善
    c = a+b
    pass
```
14. 在某处代码添加书签 `f11`
15. 使用Sourcery插件优化代码 `alt+shift+enter`
16. 设置代码文件模板
>file -> setting -> Editor -> File and Code Templates -> Python Script
```python
# -*- encoding: utf-w -*-
"""
${PRODUCT_NAME} ${NAME}
${YEAR}年${MONTH}月${DAY}日
by developer
"""
```
17. 使用实时模板快速添加代码段
>file -> setting -> Editor -> Live Templates
18. 查看当前文件的变量和函数结构
> 左下方 Structure
19. 在工程全局搜索某个变量 `ctrl+shift+f`
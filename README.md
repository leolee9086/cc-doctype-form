# cc-doctype-form
# 安装

- 将源码放进思源笔记工作空间的widgets目录即可
  - data
    - widgets
      - cc-doctype-form   

# 功能:

- 展示数据源块的属性
- 修改属性时会实时变更到界面

# 注意

- 需要同时安装cc-baselib方可使用
- 所有的属性实际上都是文本值,只是做了不同的展示
- 改成思源的原始属性时可以使用"原始文本"属性类型
- 因为需要操作DOM所以在应用模式下插入的挂件可能在浏览器中失效,反之亦然.

# 效果预览和建议

大致效果如下
![)J9I{8 0L9_4QF@KJ6EPQ0A](https://user-images.githubusercontent.com/19915077/147845794-5af9833c-7a8b-4d5e-8bba-63e0c09b992f.png)
建议通过iframe访问以规避ip变化时挂件失效的问题
可以放在文章顶部用来当成属性面板的快捷入口

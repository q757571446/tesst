# HTML 转 Markdown 综合演示

本页面包含各种 HTML 元素，转换后可以测试对 **语义元素**、*格式化文本*、 列表、表格、代码、媒体等的支持。

## 语义元素示例

### 三级标题

#### 四级标题

这是一个段落，包含 **加粗文本**、*斜体文本*、`内联代码`、以及 [超链接](https://www.baidu.com "示例链接")。

还支持 删除线、**高亮文本**、HTML (HyperText Markup Language)、`Ctrl+C` 键盘输入、H<sub>2</sub>O 下标和 x<sup>2</sup> 上标。

> 这是一个引用块。
> 
> 引用可以包含多个段落。
> 
> > 还可以嵌套引用。

---

## 列表示例

### 无序列表

-   列表项 1
-   列表项 2
    -   嵌套项 2.1
    -   嵌套项 2.2
-   列表项 3

### 有序列表

1.  第一项
2.  第二项
3.  第三项

### 任务列表（GFM）

-   [x]  已完成任务
-   [ ]  待完成任务
-   [x]  另一个已完成任务

### 定义列表

**HTML**
:   超文本标记语言
**CSS**
:   层叠样式表

## 表格示例（GFM）

姓名

年龄

分数

张三

25

95

李四

28

88

王五

22

92

## 代码示例

内联代码示例：`const x = 42;`

### JavaScript 代码块

```javascript
function greet(name) {
  console.log(`Hello, ${name}!`);
}

greet('World');
```

### Python 代码块

```python
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)

print(fibonacci(10))
```

## 媒体元素

### 标准图片

![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)

### 带宽高属性的图片

<img src="https://sf16-sg.tiktokcdn.com/obj/eden-sg/hubseh7bsbps/20251208-160108.png" alt="InfoQuest Banner" width="600" />

### 图片与标题（Figure）

<figure>
  <img src="https://img.shields.io/badge/python-3.12+-blue.svg" alt="Python 3.12+" />
  <figcaption>图 1: Python 版本徽章</figcaption>
</figure>

### GitHub 视频（user-attachments URL）

https://github.com/user-attachments/assets/f3786598-1f2a-4d07-919e-8b99dfa1de3e

### 音频（转换为下载链接）

[🔊 url?id=447925558.mp3](http://music.163.com/song/media/outer/url?id=447925558.mp3)

## 表单元素

姓名： **得到的** 

邮箱：

国家/地区： [美国] 

掌握的编程语言（多选）：

性别：

[ ] 男
[ ] 女

兴趣爱好：

[ ] 阅读
[ ] 运动
[ ] 音乐

备注：

[ ] 订阅新闻通讯

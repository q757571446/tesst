# HTML 转 Markdown 综合演示

本页面包含各种 HTML 元素，转换后可以测试对 **语义元素**、*格式化文本*、 列表、表格、代码、媒体等的支持。

## 语义元素示例

### 三级标题

#### 四级标题

这是一个段落，包含 **加粗文本**、*斜体文本*、`内联代码`、以及 [超链接](https://example.com "示例链接")。

还支持 ~删除线~、**高亮文本**、HTML (HyperText Markup Language)、`Ctrl+C` 键盘输入、H<sub>2</sub>O 下标和 x<sup>2</sup> 上标。

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
-   [x]  待完成任务
-   [x]  另一个已完成任务

### 定义列表

**HTML**
:   超文本标记语言
**CSS**
:   层叠样式表

## 表格示例（GFM）

| 姓名 | 年龄 | 分数 |
| --- | --- | --- |
| 张三 | 25 | 95 |
| 李四 | 28 | 88 |
| 王五 | 22 | 92 |

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

### 图片

![示例图片](https://via.placeholder.com/400x200 "这是一个示例图片")

### 图片与标题（Figure）

![图表](https://via.placeholder.com/300x200 "图 1: 示例图表")

### 视频（转换为链接）

<!-- video: http://localhost:5173/example.mp4 (width: 400, height: 300) -->
[视频: 您的浏览器不支持视频标签](http://localhost:5173/example.mp4)

### 音频（转换为链接）

[音频: 您的浏览器不支持音频标签](http://localhost:5173/example.mp3)

## 表单元素

姓名：

邮箱：

国家/地区： [中国] 

性别：

[ ] 男[ ] 女

兴趣爱好：

[ ] 阅读[x] 运动[x] 音乐

备注：

[ ] 订阅新闻通讯

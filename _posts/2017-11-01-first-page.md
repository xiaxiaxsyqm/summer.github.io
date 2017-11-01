# css居中 
## 水平居中
### 行内(inline)或者inline-*元素（如文本或链接）
将inline元素包裹在块状元素内，使用：
```
.center-children {
	text-align: center;
} 
```
这种方法用于`inline`,`inline-block`,`inline-table`,`inline-flex`等类型的元素。
### 块状(block)元素
可以将该元素的`margin-left`和`margin-right`的值设置为`auto`（前提是该元素已经设置了width）：
``` 
.center-me{
	margin: 0 auto;
}
```
### 多个块状元素



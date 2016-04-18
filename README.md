# css3
## 伪类选择器
> :before 
> :after
```css
/* 清除浮动*/
.clf:after,.clf:before{
	content:"";
	display:block;
	clear:both;
}
```
4.属性选择器
- [attr] 选中带有指定属性的元素
- [attr=value]选中带有指定属性和值得元素
- [attribute~=value]选中值中含有指定字符的元素(匹配的时候是包含单词)
- [attribute|=value] 选中
- [attribute^=value]  a[src^="https"]  选择其src属性值以 "https" 开头的每个 <a> 元素
## border-radius
- 4个值：border-radius: 左上 右上 右下 左下；
- 3个值：border-radius: 左上 右上 左下 右下;
- 2个值：border-radius: 左上 右下 右上 左下；
- 1个值：border-radius: 四角;
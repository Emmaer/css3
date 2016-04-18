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
# News-Website-Project-by-bootstrap
通过bootstrap设计一个新闻网站
bootstrap自带响应式布局<br>
块布局要记得清除浮动-"clearfix"<br>
配用于移动端代码:<br>
```html
<label id="toggle-label" class="visible-xs-inline-block" for="toggle-checkbox">MENU</label>
<input class="hidden" type="checkbox" id="toggle-checkbox">
```

```css
#toggle-checkbox:checked ~ div {
	display: block !important; 
}

#toggle-label {
	display: inline-block;
	position: absolute;
	right: 15px;
	top: 13px;
	font-size: 16px;
	font-weight: normal;
	color: #666;
	cursor: pointer;
	display: none;
}

#toggle-label:hover {
	color: #333;
}
```

效果图:<br>
![images](https://github.com/bzy008/News-Website-Project-by-bootstrap/blob/master/images/%E9%A6%96%E9%A1%B5.png)
![images](https://github.com/bzy008/News-Website-Project-by-bootstrap/blob/master/images/%E6%96%B0%E9%97%BB.png)
![images](https://github.com/bzy008/News-Website-Project-by-bootstrap/blob/master/images/%E6%B3%A8%E5%86%8C.png)
辅助课程可浏览biaoyansu.com

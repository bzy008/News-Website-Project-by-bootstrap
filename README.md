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

效果图

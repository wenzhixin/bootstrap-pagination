bootstrap-pagination
====================

jQuery bootstrap pagination plugin


## Options: 

```
items_per_page: 10, //每页的 item 数

num_display_entries: 5, //显示的页码数

current_page: 0, //当前页

num_edge_entries: 1, //前后显示的页码数

link_to: "javascript:void(0)", //链接地址

prev_text: "«", //上一页

next_text: "»", //下一页

ellipse_text: "...", //显示的省略文本信息

prev_show_always: true, //是否一直显示上一页

next_show_always: true, //是否一直显示下一页

callback: function(page, component) {} //点击时的回调函数
```

## How to use:

```
$('element').pagination(number, {
	callback: function(page, component) {
		console.info(page);
	}
});
```
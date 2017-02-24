# html_foreach
foreach in html tag

```html
<ul>
	<li data-loop="json_data as key, value">
		<b>{{value.id}} -> {{value.name}}</b>
	</li>
</ul>
```

```js
json_data = [ { id : 1, name : "test" }, { id : 2, name : "peji" } ];
```

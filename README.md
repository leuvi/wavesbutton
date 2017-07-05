## Install:

```javascript
npm install waves-button --save
```

## Use:

```html
<ul id="list">
	<li>list1</li>
	<li>list2</li>
	<li>list3</li>
</ul>
```

```javascript
import WavesButton from 'waves-button'

const lis = document.querySelectorAll('#list li')
[...lis].forEach(li => {
	new WavesButton(li, '#ff348b')
})
```


# Command

```js
Array.from(document.getElementsByClassName('circle-list-item')).forEach(i=>{console.log(`[${i.getElementsByClassName('circle-name')[0].innerText}](https://techbookfest.org${i.getAttribute('href')})`)})
```

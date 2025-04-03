# tinyQuery
<br><br>
https://iluso-6.github.io/
<br><br>
***I came across this somewhere, the entire file contents of tinyQuery.js***
```javascript
function _T(selector, container) {
    return (container || document).querySelector(selector);
}
```
<br><br>
Example usage
```javascript
   _T('#Some Div').addEventListener('click', function(){
	// do something here...
	});
```

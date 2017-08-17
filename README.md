# tinyQuery
<br><br>
***I came across this somewhere, the entire file contents of tinyQuery.js***
```javascript
function _T(selector, container) {
    return (container || document).querySelector(selector);
}
```
<br><br>
Example usage
```
   _T('#Some Div').addEventListener('click', function(){
	// do something here });
```

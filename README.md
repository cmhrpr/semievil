# semievil
Want to cause frustration but not totally screw up someone's system? Look no further

### JavaScript
[Random replace for added fun](https://www.reddit.com/r/ProgrammerHumor/comments/519akm/a_fun_line_of_javascript_to_hide_in_a_coworkers/)
```javascript
setInterval(function(){ 
	var x = document.querySelectorAll('*');
    x[Math.floor(Math.random() * x.length)].innerText = String.fromCharCode(112,101,110,105,115);
}, 10000);
```

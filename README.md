#A Pulldown Thingey
####(I hate the word Widget, but thats what it is)

Creating a pulldown widget thingey in pure JavaScript, with no dependencies. Its designed to work in modern browsers, which in this case does mean IE8.

Will use CSS3 animations and fallback to JavaScript animations ( in progress ). 

##Using

Include the pullDownWidget.css and pullDownWidget.js in your page:

```html
<link rel="stylesheet" href="pullDownThingy.css">
<script type="text/javascript" src="pullDownThingy.js"></script>
```
This will create a global varible called pullDownThingy.

Then tell the thingy what content to use by using a CSS selector:

```javascript
document.onreadystatechange = function( ){
                
    if( document.readyState == 'complete' ){
        pullDownThingy.init( '#pull' );
    }
};
```

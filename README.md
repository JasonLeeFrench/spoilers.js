spoilers.js
===========

Hide yo' spoilers!

Hover over spoilers to reveal them partly, click to reveal completely.

Click the toggler - turn on/off all spoilers at once!

Based on [Times' Gone Girl review](http://time.com/3418766/gone-girl-movie-review/).

Basic usage
-----------

```
$(document).ready(function(){
  $('.spoiler').spoilers();
});
```

Additional options
------------

```
$(document).ready(function(){
  $('.spoiler').spoilers({
      'maxBlur': 4, // Set how blurry you want your spoilers. 4 is default.
      'partBlur': 2, // How blurry spoilers are when hovered over. 2 is default.
      'toggler': '#toggle' // Toggle spoilers on/off when clicked.
  });
});
```

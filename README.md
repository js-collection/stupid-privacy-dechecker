# stupid-privacy-dechecker

--- 

#### WHAT IS IT?
It's a stupid script to copy and past in console to uncheck in one shot all privacy checkboxes

--- 

#### WHY THIS?

😤  I'm tired of having to tick boxes to avoid selling off my data to call centers via sites. For this purpose, for help everyone and for not rewrite it every time... I release this stupid script.

--- 

#### HOW TO USE?

On the site, open console use the Chrome shortcut by pressing your keyboard's Cmd+Option+J (for Mac) or Ctrl+Shift+J (Windows, Linux, Chrome OS)

Copy and past this in console:
```js
(()=>{let checks = document.querySelectorAll("input[type=checkbox]");for (let input of checks) {input.checked=false;input.removeAttribute('checked')}})()
```

Press enter end et voilà! All checked is unchecked 👻 

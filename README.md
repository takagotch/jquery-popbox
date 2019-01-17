### jquery-popbox
---
https://github.com/gristmill/jquery-popbox

```js
$(document).ready(function(){
  $('.popbox').popbox();
});

$(document).ready(function(){
  $('.popbox').popbox({
    'open' : '.open',
    'box' : '.box',
    'arrow': '.arrow',
    'arrow_border': '.arrow',
    'close': '.close',
  });
});




```

```
<script type='text/javascript' charset='utf-8' src='jquery.js'></script>

<div class='popbox'>
  <a class='open' href='#'>Click</a>
<div class='collapse'>
  <div class='box'>
    <div class='arrow'>
    <div class='arrow-border'>
      <a href="#" class="close"></a>
    </div>
    </div>
  </div>
</div>
```

```
```


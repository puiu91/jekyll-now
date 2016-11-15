---
layout: default
title:  "Pretty ternary code in php"
date:   2016-11-15 16:27:00
categories: main
---

Some sample code below.

```php
<?php

function validateInput($input)  
{
    return ( 

        ! $this->is_array($input) or 
        ! $this->areCoordinatesValid($input)

    ) ? true : false;
}
```

``` js
document.getElementById("demo").innerHTML = 5 * 10;
```

# get_browser
Alternative to function get_browser


## Simple Example
-----------------
```php
include("../autoload.php");

$getBrowser = _get_browser();
print "Your browser: {$getBrowser->parent} on {$getBrowser->platform};
print_r($getBrowser);
```

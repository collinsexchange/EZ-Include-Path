# PHP - EZ-Include-Path

EZ-Include-Path provides a simple and clean way to use absolute paths with PHP's include construct allowing developers to include files into php scripts without the need for autoloading. Zero dependencies.

## Install
``` git clone (url) . ```

``` cd /to ```

### Usage
```include_once "../path.php";```

*Example*
```
// include_once Path::match(this, $_SERVER['DOCUMENT_ROOT']."/EZ-Include-Path/to/connecting_class.php");

//Example 2: connecting_class defined in path.php
include_once Path::match(this, connecting_class);

connecting_class::test(); 
```

#### `connecting_class::test();`   

```
EZ-Path works!
```

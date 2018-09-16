# console.php - PHP DevTools console
## about console.php
console.php is an innovative program that can be output to the DevTools console of the browser.
It also supports Error.
And it also supports numbers and boolean, array, objects.
Some browsers can also decorate letters.
## Usage
In use it must first be instantiated.
~~~ PHP
$console_name = new console();
~~~

After that only you call a method in the usual way in PHP.
These arguments are the same as Javascript.
Since example exists, also good to look an [exsaple.php](./exsample.php) sourcecode.
~~~ PHP
$main_console->log( 'Hello', 'World', '!' );
$main_console->log( '%cYellow', 'color: yellow;' );
~~~

## LICENSE
console.php is licensed under a dual license of MIT and [PAL 1.1](https://github.com/mk7087/PublicAdjustingLicense)
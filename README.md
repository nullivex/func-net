openlss/func-net
====

Networking helper functions (IP formatting, conversions, etc)

Usage
====

```php
//fetch a URL with POST vars
$content = net_curl_post("http://some.site.net/action.cgi",array('some_var'=>'value'));
```

Reference
====

### (string result) net_curl_post($url,$vars=array(),&$ch=null)
Sets up a POST request via curl, returns the response content.
Optionally accepts a pointer via which to return the curl handle.

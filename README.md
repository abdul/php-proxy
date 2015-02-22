PHP Proxy can be used to get around crossdomain security restrictions in browser. It can be used to load text/binary data. 

Usage:

```
http://yourserver.com/proxy.php?url=<url_encoded_desitnation_url>[&mimeType=<mimeType>]
```

Examples:

- Load XML/Text: http://yourserver.com/proxy.php?url=http%3A//abdulqabiz.com/blog/index.xml

- To load a SWF (binary-data): http://yourserver.com/proxy.php?url=http%3A//abdulqabiz.com/files/some.swf&mimeType=application/x-shockwave-flash

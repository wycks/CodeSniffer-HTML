### CodeSniffer XML report rendered as HTML

These files will render a [PHP_CodeSniffer](http://pear.php.net/package/PHP_CodeSniffer) as HTML, see screenshot.

**Instructions:**

`<?xml-stylesheet type="text/xsl" href="http://example.com/PHP-Codesniffer.xsl"?>`  
Goes in your XML file after the XML tag, see  *example.xml*.

Will not work on localhost due to security with xml-stylesheet, must be an actual URL.
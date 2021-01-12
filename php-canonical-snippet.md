# Description
***PHP Snippet to generate a cannonical (Good for SEO)***

# Single line
```
<link rel='canonical' href='<?= (isset($_SERVER['HTTPS']) && $_SERVER['HTTPS'] === 'on') ? "https://" : "http://".strtok($_SERVER['HTTP_HOST'] . $_SERVER['REQUEST_URI'], "?"); ?>'>
```

# Working with examples

***example.com/***

***example.com/page.html***

***example.com/page.html/***

***example.com/page.html?pr=something&sp=number***

***example.com/page.html/?pr=something&sp=number***

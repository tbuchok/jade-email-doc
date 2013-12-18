# jade-email-doc

Stop worrying about the junk stuff in the header. 

Use this instead. 

[Read more about Modern HTML Email](http://modernhtmlemail.com/)

## How it works

Write email code in Jade, using `+doc` for the mixin:

```jade
include ../email-doc.jade

+doc(title = 'Lorem ipsum dolor!')
```

And get a much more intense output, voila!

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.ord/1999/xhtml">
  <head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1"/>
    <title>Lorem ipsum dolor!</title>
  </head>
</html>
```
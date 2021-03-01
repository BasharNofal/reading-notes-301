## Partials

**Partials** in ejs is similar to functions in normal JavaScript, it allow you to use section of the HTML code in multiple files using ejs.

**Partials** are usually used in header and footer so what you do is write the HTML code once and then link it in multiple files, This can be done by:

* Write your code inside of a file with extension `.ejs`.
* Write `<%-include(path)%>` where you want to reuse the section of the code.
* Note that the path is without the extension of the file.

![partials](https://i.stack.imgur.com/Jt4nj.png)
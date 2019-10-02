**CSS**

*allows you to create rules that control the way that each individual box (and the contents of that box) is presented.*


<link> chapter-10/using-external-css.html HTML
The <link> element can be used in an HTML document to tell the
browser where to find the CSS file used to style the page. It is an
empty element (meaning it does not need a closing tag), and it
lives inside the <head> element.

### It should use three attributes:
href
This specifies the path to the
CSS file (which is often placed in
a folder called css or styles)

<style>
You can also include CSS rules within an HTML page by placing
them inside a <style> element,which usually sits inside the
<head> element of the page. 


There are many different types of CSS selector that allow you to
target rules to specific elements in an HTML document.
 If you specify the font-family or color properties on the
<body> element, they will apply to most child elements. This is
because the value of the font-family property is
inherited by child elements. It saves you from having to apply
these properties to as many elements (and results in simpler
style sheets).

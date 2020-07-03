[HOME](https://dinaalsaid.github.io/reading-notes/)  &nbsp; [NEXT](https://dinaalsaid.github.io/reading-notes/) 


# Introduction 
## Web pages

Most web pages these days are structured using HTML and styled using CSS, that are recieved by a host from a server, in which the browser at the host interprets to present a web page for the user.
For small websites this is enough usually, but for larger websites databases for storing and handling users' information is required.

## Website Structure and HTML

**HTML** describes the structure of a web page using tags to make it more readable.
for example if we want to create a heading (bold and larger font size) we can use the following code:

````HTML
    <h1> Heading content </h1>
````
An HTML element is made up of an opening and a closing tag and the content inside.

![HTML tags](https://lh3.googleusercontent.com/proxy/lqnjNsaaTJG9OVuTpxYPPm6hxiq3ZPQh1TGCzMUcXAX9ZCmn_MN_QRQDh7ElqsIz16Il8VsSxSPYNronkmCMfmx9hUqkkpYPDNjzY6S39yA)

Some elements do not contain content therefore only consist of one tag (do not have a closing tag)


Elements have attributes to describe them. for example:

````HTML
    <p lang="fr">Paragraphe en Français</p>
````

<!-- ## HTML versions

* HTML4 : released in 1997
* XHTML : releaased in 2000
* HTML5 : released in 2000 and is the one commonly used recently. -->
The versions are indicated in the beginning of an HTML file through the DOCTYPE tag.

## Block and Inline elements 

&nbsp;|Block element|Inline element
--------|------|-----------
definition|starts on a new line | continues on the same line as neighbouring elements.
examples|<h1>, <p>, <ul>, and <li> |<a>, <b>, <em>, and <img>
useful elementts|div element to group inline and block elements |span element to group inline elements

## Some escape charecters
Escape characters are used to include special characters in your pages such as <, >, and ©.

* `&lt;` or `&#60;` for <
* `&amp;`; or `&#38;` for &
* `&copy;` or `&#169;` for copyright symbol
* `&gt;` or `&amp;` for >

## HTML 5

### traditional HTML

![trad html](images/traditional-html.PNG)
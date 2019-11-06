# OnePageSite
It's my portfolio !


## Main features:

### Hamburger Menu:
* Showing up when page width is less or equal 600px.

Code:

```javascript
function hamburger() {
    var x = document.getElementById("top-nav");
    if (x.className === "top-nav") {
        x.className += " responsive";
    } else {
        x.className = "top-nav";
    }
}
```

* That simple script looking for element in document and adding new class for this element ("responsive"), and then magic happens ! In CSS file there's .resonsive rules which changing navbar look.

![Alt Text](/images/hamburger.gif)

***

### Grid system

* Grid system adapted to many screen resolutions. Now the site is responsive !

![Alt Text](/images/RWD.gif)


***


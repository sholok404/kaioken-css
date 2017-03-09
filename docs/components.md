# Kaioken*2!(components)

There are not a lot of components in Kaioken CSS and even the ones included
are very stripped down.

## Navbar

The navbar is very simple. It basically removes any styling from lists and links.

### Vertical navbar:
```
<nav class="navbar">
    <ul>
        <li><a href="#">Link</a></li>
        <li><a href="#">Link</a></li>
        <li><a href="#">Link</a></li>
        <li><a href="#">Link</a></li>
    </ul>
</nav>
```
### Horizontal navbar:
```
<nav class="navbar">
    <ul class="grid grid-around">
        <li><a class="col-1" href="#">Link</a></li>
        <li><a class="col-1" href="#">Link</a></li>
        <li><a class="col-1" href="#">Link</a></li>
        <li><a class="col-1" href="#">Link</a></li>
    </ul>
</nav>
```

### Horizontal fixed navbar:
```
<nav class="navbar navbar-fixed">
    <ul class="grid grid-around">
        <li><a class="col-1" href="#">Link</a></li>
        <li><a class="col-1" href="#">Link</a></li>
        <li><a class="col-1" href="#">Link</a></li>
        <li><a class="col-1" href="#">Link</a></li>
    </ul>
</nav>
```

## Footer

The footer is basically a 100% width container with 7% padding. Not really much.
You can also use the ```
footer-fixed
```
class to create a fixed footer.

## Media
### Classes:
* Responsive images: ```img```
* Responsive videos: ```video```

## Helper tags
The ```hidden``` class makes an element completely invisible. The ```invisible```
class makes an element visually invisible. ```clearfix``` does what it says (if you don't know what that is, Google it up).

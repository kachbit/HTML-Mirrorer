# HTML-Mirrorer
* API that converts HTML to HTML. 
* Retrieve a webite url that will display your desired content.

## Useful For
* Dynamically generated iframes
* Effortlessly rendering static pages

## Usage
Use the API endpoint ``https://kachbit.github.io/HTML-Mirrorer``, and set the url parameter ``data`` to your url-encoded HTML string.<br>

### Example:
```url
https://kachbit.github.io/HTML-Mirrorer/?data=<h1>Rendered HTML<%2Fh1>
```
This url mimics the functionality of a website that contains ``<h1>Rendered HTML</h1>`` in its html source 

## Supports
* Javascript tags
* CSS styling
* Basically all front-end web features

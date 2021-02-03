# Graphic Elements & Accents
---

## Line before text
Add lines using pseudo elements.

**Type**: Global
**Usage**:
1. Rename and add the 2 classes below to site.css
2. Add the class name to your widget HMTL
```
.my-class-name p {
    color: rgba(0,0,0) !important;
    font-family: 'your site font name goes here', sans-serif !important;
    font-size:14px !important;
    font-weight:500 !important;
    letter-spacing: 3px !important;
    text-transform: uppercase !important; 
}
.my-class-name p::before {
    background-color: rgb(0,0,0);
    content: '';
    display: inline-block;
    height: 1px;
    margin-right: 8px;
    width: 60px;
    vertical-align: middle;
}
```
**Example**:
This example adds a black box with height of 1px and 60 px in width (basically, a line) before the text in the widget.
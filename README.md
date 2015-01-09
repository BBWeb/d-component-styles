# d-component-styles
A Derby plugin for adding the possibility to define (links to) styles on a component level

How to use
==========
Adds the possibility to add a style-property on your Component prototype with a link to a stylesheet (or .styl, etc.), which will automatically be added when the component is added. I.e. it works very similar to defining the view on the component. E.g.

```javascript
// When this component is loaded through app.component('./mycomponent/index.js'), the stylesheet in './mycomponents/styles/index.styl' will automatically be added
function MyComponent () {}

MyComponent.prototype.style = __dirname + '/styles'
```

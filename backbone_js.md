## Backbone JS

#### Creating a view

Create a `Backbone.View` object and attach it to the DOM. Calls render within the view initialization. Preserves `this` within functions.

The way to create new objects is to extend Backbone objects.

When appending a view object, you can chain calls and then access the `el` property of the view like:

    itemView.render().el

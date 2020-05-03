# 66. Binding to Custom Properties
- All properties of a component are only accessible inside the component. Not from outside. And that's a good thing.
- You have to be explicit about which property you want to expose
- If you want a parent component to be able to bind to its child property, you need to add something to that property. You need to add a decorator. 
- We use `@Input` decorator to expose it. So any parent hosting `element` can now bind to element.
- 
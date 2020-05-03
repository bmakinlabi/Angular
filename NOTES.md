# 72. More on View Encapsulation
- In the last lecture you learn how Angular encapsulate your styles. You can override those encapsulation though.
- If you use `ViewEncapsulation.None` by using `None`, you won't see those strange characters being added to your CSS class in the Chrome inspect.
- Now, if you do that, if you can add a css class to the css file of the component, they'll now get applied globally. All components that uses that attributes or that matches that CSS class or html attribute will now start using that CSS rule. 
- You probably don't want to use it but it's good to know that you can change it. 
- `Emulated` is the default anyway and you wouldn't want to add it. It's working well. You can leave it there or remove it. 
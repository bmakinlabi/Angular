# 75. Getting Access to the Template & DOM with @ViewChild
- There's another way to getting access to local references or any element directly from our TS code.
- Note: **With Angular 8, that should be @ViewChild('...', { static: true}) since we'll also use the selected element in ngOnInit**
- If you don't want to pass a string into `@ViewChild` but wants to select a component, you can simply pass the component.
- The `'serverContentInput'` has a reference of `ElementRef` which makes us put it in the code of type. Note that we got the reference through the `console.log`
- `ElementRef` is a angular type.
- Note that `ElementRef` has an underlying native element. That too also appeared on `console.log`. I might need to start console.logging before writing some of these code. 
- By doing it like this, we get direct access to our DOM template through `ViewChild`
- We're not using two-way binding here like we did before. We're now using local references. Note that as you've learned in the previous lecture and this, there are two ways to fetch local references. 
- Don't use these things to directly output something in the dom like doing this: `this.serverContentInput.nativeElement.value = 'Something'` Don't do that to change the value directly yourself. There's an alternative that's highly recommended. You'll learn it later in the directives. Generally, you should use the other tools like string interpolation and property binding if you want to output something in the DOM. 
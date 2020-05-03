# 77. Understanding the Component Lifecycle
- `ngOnChanges` is right at the start when a new component is create. Executes multiple times. Called after a bound input property changes
- `ngOnInIt` - Called once the component is initialized. That doesn't mean we can see it yet.
- `ngDoCheck` - Called during change detection run.
- `ngAfterContentInit` - Called after content (ng-content) has been projected into view.
- `ngAfterContentChecked` - Called every time the projected content has been checked.
- `ngAfterViewInit` - Called after the component's view (and child views) has been initialized.
- `ngAfterViewChecked` - Called every time the view (and child views) have been checked.
- `ngOnDestroy` - Called once the component is about to be destroyed
- Reference page for learning Lifecycle Hooks: https://angular.io/guide/lifecycle-hooks
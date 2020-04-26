# 37. Enhancing ngIf with an Else Condition
- `#` is a local reference on the element. Instructor will talk about it later. See it as a marker. 
- `ng-template` is a component directive. Use it to mark places in the DOM. 
- Wow. That comes up and it gets replace after clicking the button. This is so cool.
- We deleted it. But it's so nice that I'm adding it below here:
```html
<p *ngIf="serverCreated; else noServer">Server was created, server name is {{ serverName }}</p>
<ng-template #noServer>
    <p>No server was created!</p>
</ng-template>
<app-server></app-server>
```
- Study it. 
-  
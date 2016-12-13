# angular2-material-chips
Angular 2 Material Chips Directive/Component with no dependencies required.
This is a Material Chips  Directive/Component for Angular 2.

# Demo page
http://shootermv.github.io/angular2-material-chips/examples/index.html

# Installation
```bash
npm i --save angular2-material-chips
```

# Usage
* Use it in your HTML elements, for example:
```html
<material-chips [(ngModel)]="tags" ></material-chips>
```

* Add MaterialChipsModule in your app.module.ts:
```javascript
import {MaterialChipsModule} from 'angular2-material-chips';

@NgModule({
    ...
    imports: [BrowserModule, MaterialChipsModule, FormsModule]
})

```
# ContextMenu

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.3.

## How to use `ng-pro-context-menu`

Run `npm i ng-pro-context-menu`

Import `ContextMenuModule` from `ng-pro-context-menu` and include in your maine module inside imports.

Add placeholder tag `<context-menu></context-menu>` for context menu in the bottom of parent most component, which is in default `app.component.html` 

Now just add `[rightClickMenu]` and pass menu titles and `(onMenuClicked)` event handler for menu clicked.

E.g. `<span [rightClickMenu]="['Menu 1', 'Menu 2', 'Menu 3']" (onMenuClicked)="contextMenuClickedHandler($event)">Right Click on me!!!</span>`

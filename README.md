# ContextMenu

This is a simple and easy to use, angular based `Context Menu`. It can be implemented in any angular based application in few steps.

## How to use `ng-pro-context-menu`

  1. Run `npm i ng-pro-context-menu`

  2. Import `ContextMenuModule` from `ng-pro-context-menu` and include in your maine module inside imports.

  3. Add placeholder tag `<context-menu></context-menu>` for context menu in the bottom of parent most component, which is in default `app.component.html` 

  4. Now just add `[rightClickMenu]` and pass menu titles and `(onMenuClicked)` event handler for menu clicked.

E.g. `<span [rightClickMenu]="['Menu 1', 'Menu 2', 'Menu 3']" (onMenuClicked)="contextMenuClickedHandler($event)">Right Click on me!!!</span>`

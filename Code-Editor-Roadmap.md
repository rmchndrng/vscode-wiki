
## Cursor

* [issue #11150](https://github.com/Microsoft/vscode/issues/11150): Changing multiple occurrences when they are adjacent loses one of the occurrences
* move actions that don't need a view model out of the editor core:
  - [ ] deleteAllRight (**@alex**)

## Indenting/Outdenting

* [issue #9409](https://github.com/Microsoft/vscode/issues/9409): Outdent issue with Typescript
* [issue #15598](https://github.com/Microsoft/vscode/issues/15598): Multi-line indents do not preserve partial indents
* [issue ##2272](https://github.com/Microsoft/vscode/issues/2272): Automatically indent "end" for ruby code

## Find widget
* [issue #15579](https://github.com/Microsoft/vscode/issues/15579): Regex search issue
  * seed search string only if the selection is created explicitly (i.e. not due to a find match)

## DVORAK on mac
* multiple keybindings issues, involves Chromium implementing a very poor w3c recommendation

## multicursor
* [issue #16486](https://github.com/Microsoft/vscode/issues/16486): Deselect one of multi-cursors

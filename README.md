# VS Code Settings

This repository contains my personalized Visual Studio Code settings in `settings.json`. Below is an explanation of each setting and what it does.

## Appearance Settings

- `"editor.bracketPairColorization.enabled": false`  
  Disables bracket pair colorization in the editor.

- `"editor.glyphMargin": false`  
  Hides the glyph margin on the left side of the editor.

- `"workbench.productIconTheme": "fluent-icons"`  
  Sets the product icon theme to "fluent-icons".

- `"editor.scrollbar.horizontal": "hidden"`  
  Hides the horizontal scrollbar in the editor.

- `"editor.scrollbar.vertical": "hidden"`  
  Hides the vertical scrollbar in the editor.

- `"window.density.editorTabHeight": "compact"`  
  Sets the editor tab height to compact.

- `"editor.accessibilitySupport": "off"`  
  Disables accessibility support in the editor.

- `"symbols.hidesExplorerArrows": false`  
  Shows arrows next to folders in the explorer.

- `"workbench.iconTheme": "quill-icons"`  
  Sets the workbench icon theme to "quill-icons".

- `"workbench.activityBar.location": "hidden"`  
  Hides the activity bar.

- `"workbench.layoutControl.enabled": false`  
  Disables the layout control.

- `"workbench.editor.editorActionsLocation": "hidden"`  
  Hides editor action buttons.

- `"workbench.editor.empty.hint": "hidden"`  
  Hides the empty editor hint.

- `"window.zoomLevel": 0`  
  Sets the window zoom level to default (no zoom).

## General Settings

- `"window.openFilesInNewWindow": "off"`  
  Opens files in the existing window instead of a new one.

- `"editor.tabSize": 2`  
  Sets the tab size to 2 spaces.

- `"editor.folding": false`  
  Disables code folding.

- `"editor.insertSpaces": false`  
  Uses tabs instead of spaces for indentation.

- `"editor.smoothScrolling": true`  
  Enables smooth scrolling in the editor.

- `"editor.minimap.enabled": false`  
  Disables the minimap on the right side of the editor.

- `"editor.detectIndentation": true`  
  Automatically detects indentation style from the file.

- `"editor.linkedEditing": true`  
  Enables linked editing for HTML and XML tags.

- `"editor.renderControlCharacters": false`  
  Hides control characters in the editor.

- `"editor.unicodeHighlight.ambiguousCharacters": false`  
  Disables highlighting of ambiguous Unicode characters.

- `"editor.suggestSelection": "first"`  
  Automatically selects the first suggestion in IntelliSense.

- `"html.completion.attributeDefaultValue": "singlequotes"`  
  Uses single quotes for default attribute values in HTML.

- `"editor.multiCursorModifier": "ctrlCmd"`  
  Sets the modifier for multi-cursor selection to `Ctrl` or `Cmd`.

- `"git.enableSmartCommit": true`  
  Enables smart commit when no staged changes are available.

- `"editor.stickyScroll.enabled": false`  
  Disables sticky scroll in the editor.

- `"workbench.tree.enableStickyScroll": false`  
  Disables sticky scroll for the explorer tree.

- `"window.commandCenter": false`  
  Hides the command center in the window.

- `"diffEditor.ignoreTrimWhitespace": false`  
  Shows trim whitespace differences in the diff editor.

- `"security.workspace.trust.untrustedFiles": "open"`  
  Opens untrusted files in restricted mode.

- `"window.confirmBeforeClose": "keyboardOnly"`  
  Confirms before closing the window only when a keyboard shortcut is used.

- `"git.openRepositoryInParentFolders": "never"`  
  Disables automatic opening of repositories in parent folders.

- `"editor.gotoLocation.multipleDefinitions": "goto"`  
  Jumps directly to the definition when multiple are found.

- `"workbench.statusBar.visible": false`  
  Hides the status bar at the bottom of the window.

## Word Wrap Settings

- `"editor.wordWrap": "bounded"`  
  Enables word wrapping at the column defined by `editor.wordWrapColumn`.

- `"editor.wrappingIndent": "same"`  
  Uses the same indentation for wrapped lines as the start of the line.

- `"editor.wordWrapColumn": 80`  
  Sets the word wrap column to 80 characters.

- `"editor.scrollBeyondLastLine": true`  
  Allows scrolling beyond the last line of the file.

## Tag Auto-Close Settings

- `"html.autoClosingTags": true`  
  Enables auto-closing of HTML tags.

- `"javascript.autoClosingTags": true`  
  Enables auto-closing of JavaScript tags.

- `"typescript.autoClosingTags": true`  
  Enables auto-closing of TypeScript tags.

## Font Settings

- `"editor.fontSize": 12`  
  Sets the editor font size to 12px.

- `"editor.lineHeight": 18`  
  Sets the editor line height to 18px.

- `"editor.fontWeight": "400"`  
  Sets the editor font weight to normal.

- `"editor.fontLigatures": true`  
  Enables font ligatures in the editor.

- `"editor.fontFamily": "PragmataPro Mono Liga, JetBrains Mono, Maple Mono, Cascadia Code, IBM Plex Mono, MonoLisa, Ubuntu Mono, Geist Mono, Fira Code iScript, DejaVu Sans Mono, Fira Code, Sarala, monospace"`  
  Specifies the font family for the editor.

- `"editor.inlayHints.fontFamily": "PragmataPro"`  
  Sets the font family for inlay hints.

- `"chat.editor.fontFamily": "PragmataPro"`  
  Sets the font family for the chat editor.

- `"editor.codeLensFontFamily": "PragmataPro"`  
  Sets the font family for code lens.

- `"debug.console.fontFamily": "PragmataPro"`  
  Sets the font family for the debug console.

## Cursor Settings

- `"editor.cursorBlinking": "phase"`  
  Sets the cursor blinking style to phase.

- `"editor.cursorStyle": "line-thin"`  
  Sets the cursor style to a thin line.

- `"editor.cursorSmoothCaretAnimation": "explicit"`  
  Enables smooth caret animation when explicitly triggered.

- `"editor.hideCursorInOverviewRuler": true`  
  Hides the cursor in the overview ruler.

## Syntax Highlighting Settings

- `"editor.tokenColorCustomizations": {}`  
  Allows customization of token colors for syntax highlighting.

## Terminal Settings

- `"terminal.integrated.fontFamily": "PragmataPro Liga"`  
  Sets the font family for the integrated terminal.

- `"terminal.integrated.fontSize": 13`  
  Sets the font size for the integrated terminal to 13px.

- `"terminal.integrated.tabs.enabled": false`  
  Disables terminal tabs.

- `"terminal.integrated.cursorStyle": "line"`  
  Sets the cursor style in the terminal to a line.

## Explorer Settings

- `"explorer.confirmDelete": false`  
  Disables confirmation prompt when deleting files.

- `"explorer.confirmDragAndDrop": false`  
  Disables confirmation prompt when dragging and dropping files.

- `"explorer.compactFolders": false`  
  Expands folders fully instead of compacting them in the explorer.

- `"workbench.editor.tabSizing": "shrink"`  
  Sets the tab sizing mode to shrink.

- `"workbench.startupEditor": "newUntitledFile"`  
  Opens a new untitled file on startup.

## Debug Settings

- `"debug.toolBarLocation": "hidden"`  
  Hides the debug toolbar.

- `"debug.focusWindowOnBreak": false`  
  Keeps the focus on the current window when a breakpoint is hit.

- `"debug.showInlineBreakpointCandidates": false`  
  Disables showing inline breakpoint candidates.

- `"debug.showBreakpointsInOverviewRuler": false`  
  Hides breakpoints in the overview ruler.

## Emmet Settings

- `"emmet.includeLanguages": {}`  
  Configures languages to use Emmet for expansions.

- `"emmet.triggerExpansionOnTab": true`  
  Triggers Emmet expansions using the Tab key.

## Formatting Settings

- `"prettier.semi": false`  
  Disables semicolons in Prettier formatting.

- `"prettier.useTabs": true`  
  Uses tabs instead of spaces in Prettier formatting.

- `"editor.formatOnSave": true`  
  Formats the document on save.

- `"prettier.singleQuote": true`  
  Uses single quotes in Prettier formatting.

- `"prettier.jsxSingleQuote": true`  
  Uses single quotes in JSX Prettier formatting.

- `"prettier.arrowParens": "avoid"`  
  Avoids parentheses around a sole arrow function parameter.

- `"editor.defaultFormatter": "esbenp.prettier-vscode"`  
  Sets Prettier as the default formatter.

- `"editor.inlineSuggest.enabled": true`  
  Enables inline suggestions in the editor.

- `"editor.codeActionsOnSave": {}`  
  Configures code actions to be run on save.

- `"[prisma]": {}`  
  Configures Prisma-specific settings.

- `"[jsonc]": {}`  
  Configures JSONC-specific settings.

## Breadcrumb Settings

- `"breadcrumbs.icons": false`  
  Disables icons in breadcrumbs.

- `"breadcrumbs.showKeys": false`  
  Disables showing keys in breadcrumbs.

- `"breadcrumbs.showFiles": false`  
  Disables showing files in breadcrumbs.

- `"breadcrumbs.symbolPath": "off"`  
  Disables showing symbol paths in breadcrumbs.

## JS/TS Settings

- `"javascript.updateImportsOnFileMove.enabled": "always"`  
  Automatically updates imports when files are moved in JavaScript.

- `"typescript.updateImportsOnFileMove.enabled": "always"`  
  Automatically updates imports when files are moved in TypeScript.

- `"typescript.preferences.quoteStyle": "single"`  
  Uses single quotes in TypeScript.

- `"javascript.preferences.quoteStyle": "single"`  
  Uses single quotes in JavaScript.

- `"javascript.format.semicolons": "remove"`  
  Removes semicolons in JavaScript formatting.

- `"typescript.format.semicolons": "remove"`  
  Removes semicolons in TypeScript formatting.

- `"js/ts.implicitProjectConfig.experimentalDecorators": true`  
  Enables experimental decorators in JavaScript and TypeScript.

## Excluded File Types Settings

- `"files.exclude": {}`  
  Configures files and folders to be excluded from the explorer.

## Conclusion

These settings are tailored for a streamlined, distraction-free development experience with specific font and appearance preferences. Feel free to explore and modify them to suit your own needs.

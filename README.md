# Ponylang (VS-Code plugin for Pony)

This is a [VS-Code](https://code.visualstudio.com) plugin for the [Pony](https://www.ponylang.org/) programming language.

## Features

This project is in early development! Don't expect too much for now.

Highlevel feature list based on 
[VSCode Language Extension Guidelines](https://code.visualstudio.com/docs/extensionAPI/language-support#_configuration-based-language-support) (items are not sorted).
    
- [x] syntax highlighting (courtesy of [sublime-pony](https://github.com/ponylang/sublime-pony)).
- [ ] file icon.
- [ ] run Main.
- [ ] run tests.
- [ ] basic code snippets.
- [ ] bracket matching.
- [ ] hover for type information.
- [ ] hover for inlined documentation.
- [ ] code completion.
- [ ] diagnostics (highlight and show error information).
- [ ] show function/method signature while writing calls for it.
- [ ] go to symbol definition.
- [ ] find references to symbol.
- [ ] highlight occurrences of symbol in a document.
- [ ] show all symbol definitions in a document.
- [ ] show all symbol definitions in folder.
- [ ] quick-fixes on warnings and errors.
- [ ] codelens (actionable context information).
- [ ] rename symbols.
- [ ] format source code.
- [ ] format selected lines.
- [ ] incrementally format code as typing.

## Building

```
npm install
npm run compile
```

## Debugging

In VSCode:

- Open the debug pane (Ctrl+Shift+D)
- Run the `Launch Client` configuration.
- Once the debug VSCode instance starts, run also the `Attach to Server` configuration.

This will allow you to debug both the LSP client and server.

Code changes are compiled automatically, but require a debugger restart to take effect.

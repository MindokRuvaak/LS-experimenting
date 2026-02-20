# Viable VS Code Language Server+ Extension
## overview
NOTE: This is a fork of this [template repository](https://github.com/semanticart/minimum-viable-vscode-language-server-extension), which in turn is based upon this [sample](https://github.com/microsoft/vscode-extension-samples/tree/main/lsp-sample).

This also includes some additional features such as: 
- [x] auto indentation, auto-close brackets and stings, comment toggeling etc. following from [sample](https://github.com/microsoft/vscode-extension-samples/tree/main/language-configuration-sample)
- [ ] syntax highliting [guide](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)
- [ ] semantic highliting following [sample](https://github.com/Microsoft/vscode-extension-samples/tree/main/semantic-tokens-sample)
- [ ] (potentially) lsp log streaming? following this [sample](https://github.com/microsoft/vscode-extension-samples/tree/main/lsp-log-streaming-sample)

## build and running
1. Build the extension (both client and server) with  `ctrl+shift+B` (on windows)
2. Open the Run and Debug view and press "Launch Client" (or press `F5`). This will open a `[Extension Development Host]` VS Code window.
3. Opening or editing a file in that window should show an information message in VS Code.
4. Edits made to your `server.ts` will be rebuilt immediately but you'll need to "Launch Client" again from the primary VS Code window to see the impact of your changes.


## Distributing your extension

Note that you can package and distribute a standalone `.vsix` file without publishing it to the marketplace by following [these instructions](https://code.visualstudio.com/api/working-with-extensions/publishing-extension#packaging-extensions).

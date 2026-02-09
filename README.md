# Viable VS Code Language Server+ Extension
## overview
NOTE: This is a fork of this [https://github.com/semanticart/minimum-viable-vscode-language-server-extension][template repository], which in turn is based upon this [lsp-sample from vscode-extension-samples][sample].

This also includes some additional features such as: 
- [x] auto indentation, auto-close brackets and stings, comment toggeling etc. following from [https://github.com/microsoft/vscode-extension-samples/tree/main/language-configuration-sample][sample]
- [ ] syntax highliting
- [ ] semantic highliting following [https://github.com/Microsoft/vscode-extension-samples/tree/main/semantic-tokens-sample][sample]
- [ ] (potentially) lsp log streaming? following this [https://github.com/microsoft/vscode-extension-samples/tree/main/lsp-log-streaming-sample][sample]

## build and running
1. Build the extension (both client and server) with  `ctrl+shift+B` (on windows)
2. Open the Run and Debug view and press "Launch Client" (or press `F5`). This will open a `[Extension Development Host]` VS Code window.
3. Opening or editing a file in that window should show an information message in VS Code.
4. Edits made to your `server.ts` will be rebuilt immediately but you'll need to "Launch Client" again from the primary VS Code window to see the impact of your changes.


## Distributing your extension

Note that you can package and distribute a standalone `.vsix` file without publishing it to the marketplace by following [these instructions][vsix].

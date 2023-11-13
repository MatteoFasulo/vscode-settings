# 📝 VS Code Settings

Here are the key features that the JSON file modifies:

## 🐞 Debugging
- `debug.internalConsoleOptions`: This option is set to "neverOpen", which means the internal console will never open automatically during debugging sessions.
- `debug.javascript.debugByLinkOptions`: This option is set to "on", enabling debugging of JavaScript by link options.
- `debug.javascript.terminalOptions`: This option is currently empty, meaning no specific terminal options are set for JavaScript debugging.
- `debug.javascript.defaultRuntimeExecutable`: This option is set to use "node" for "pwa-node", specifying the default runtime executable for JavaScript debugging.

## 🐍 Python
- `python.defaultInterpreterPath`: This option is currently empty, meaning you need to provide the path to your preferred Python interpreter.
- `[python]`: 
  - `editor.formatOnType`: This option is set to false, meaning the editor will not automatically format Python code as you type.
  - `editor.defaultFormatter`: This option is set to "ms-python.autopep8", specifying the default formatter for Python code.
  - `editor.formatOnPaste`: This option is set to true, meaning the editor will automatically format Python code when you paste it.
  - `editor.formatOnSave`: This option is set to true, meaning the editor will automatically format Python code when you save it.

## 📡 Remote SSH
- `remote.SSH.externalSSH_ASKPASS`: This option is set to true, enabling the use of an external program for asking for SSH passwords.
- `remote.SSH.configFile`: This option is currently empty, meaning you need to provide the path to your SSH configuration file.

## 📝 Editor
- `editor.minimap.enabled`: This option is set to true, enabling the display of a minimap on the right side of the editor.
- `editor.inlineSuggest.enabled`: This option is set to true, enabling inline suggestions in the editor.
- `editor.fontFamily`: This option is set to "'FiraCode NF', 'firaCode Nerd Font', 'Cascadia Code', Consolas, 'Courier New', monospace", specifying the font family for the editor.
- `editor.fontLigatures`: This option is set to true, enabling the use of font ligatures in the editor.
- `editor.minimap.autohide`: This option is set to true, enabling the minimap to autohide when not in use.
- `editor.minimap.renderCharacters`: This option is set to false, meaning the minimap will not render actual characters but rather color-coded blocks.
- `editor.minimap.scale`: This option is set to 1, specifying the scale factor for the minimap.
- `editor.minimap.showSlider`: This option is set to "mouseover", meaning the minimap slider will only show when you hover over the minimap.
- `editor.minimap.side`: This option is set to "right", placing the minimap on the right side of the editor.
- `editor.cursorBlinking`: This option is set to "solid", specifying a solid cursor that does not blink.
- `editor.cursorSmoothCaretAnimation`: This option is set to "off", disabling smooth caret animation for the cursor.
- `editor.cursorSurroundingLines`: This option is set to 10, specifying the minimum number of visible lines surrounding the cursor.
- `editor.cursorSurroundingLinesStyle`: This option is set to "default", using the default style for the visible lines surrounding the cursor.
- `editor.hover.delay`: This option is set to 300, specifying the delay in milliseconds after which the hover is shown.
- `editor.guides.bracketPairs`: This option is set to true, enabling the display of guides for bracket pairs.
- `editor.guides.bracketPairsHorizontal`: This option is set to "active", meaning horizontal guides will only be shown for the active bracket pair.
- `editor.guides.highlightActiveBracketPair`: This option is set to true, enabling the highlighting of the active bracket pair.
- `editor.guides.highlightActiveIndentation`: This option is set to true, enabling the highlighting of the active indentation guide.
- `editor.guides.indentation`: This option is set to true, enabling the display of indentation guides.
- `editor.bracketPairColorization.enabled`: This option is set to true, enabling the colorization of matching brackets.
- `editor.bracketPairColorization.independentColorPoolPerBracketType`: This option is set to true, meaning each bracket type will have its own independent color pool.
- `editor.occurrencesHighlight`: This option is set to true, enabling the highlighting of symbol occurrences.
- `editor.fastScrollSensitivity`: This option is set to 5, specifying the scroll speed multiplier when pressing `Alt`.
- `editor.smoothScrolling`: This option is set to false, disabling smooth scrolling.
- `editor.stickyScroll.enabled`: This option is set to true, enabling sticky scrolling.
- `editor.dragAndDrop`: This option is set to false, disabling the ability to drag and drop text within the editor.
- `editor.wordWrap`: This option is set to "on", enabling word wrapping.
- `editor.codeLens`: This option is set to true, enabling the display of CodeLens.
- `editor.formatOnPaste`: This option is set to true, meaning the editor will automatically format pasted content.
- `editor.formatOnSave`: This option is set to true, meaning the editor will automatically format the file upon saving.
- `editor.formatOnType`: This option is set to false, meaning the editor will not automatically format after you type.

## 🎨 Workbench
- `workbench.colorCustomizations`: 
  - `editorCursor.background`: This option is set to "#ff930f", specifying the background color of the editor cursor.
  - `editorCursor.foreground`: This option is set to "#ff930f", specifying the foreground color of the editor cursor.
- `workbench.hover.delay`: This option is set to 1, specifying the delay in milliseconds after which the hover is shown.
- `workbench.list.smoothScrolling`: This option is set to true, enabling smooth scrolling for lists.
- `workbench.iconTheme`: This option is set to "vscode-icons", specifying the icon theme for the workbench.

## 🖼️ Window
- `window.menuBarVisibility`: This option is set to "compact", specifying a compact menu bar visibility.
- `window.commandCenter`: This option is set to true, enabling the command center.

## 📚 Notebook
- `notebook.lineNumbers`: This option is set to "on", enabling the display of line numbers in notebooks.

## 🌐 Live Preview
- `livePreview.customExternalBrowser`: This option is set to "Chrome", specifying Chrome as the custom external browser for live preview.

## 🛠️ C/C++
- `C_Cpp.default.compilerPath`: This option is currently empty, meaning you need to provide the path to your preferred C/C++ compiler.

## 🖥️ Terminal
- `terminal.integrated.defaultProfile.windows`: This option is set to "PowerShell", specifying PowerShell as the default profile for the integrated terminal on Windows.

## 🤖 GitHub Copilot
- `github.copilot.enable`: 
  - `*`: This option is set to true, enabling GitHub Copilot for all file types.
  - `plaintext`: This option is set to true, enabling GitHub Copilot for plaintext files.
  - `markdown`: This option is set to true, enabling GitHub Copilot for markdown files.
  - `scminput`: This option is set to false, disabling GitHub Copilot for SCM input.

## 🛡️ Security
- `security.workspace.trust.banner`: This option is set to "never", meaning the workspace trust banner will never be shown.
- `security.workspace.trust.emptyWindow`: This option is set to true, meaning an empty window will be trusted.
- `security.workspace.trust.enabled`: This option is set to false, disabling workspace trust.
- `security.workspace.trust.startupPrompt`: This option is set to "never", meaning the workspace trust startup prompt will never be shown.

## ⚙️ Settings Sync
- `settingsSync.ignoredExtensions`: This option is currently empty, meaning no specific extensions are ignored by settings sync.
- `settingsSync.ignoredSettings`: This option is currently empty, meaning no specific settings are ignored by settings sync.

## 🆚 VS Icons
- `vsicons.dontShowNewVersionMessage`: This option is set to true, meaning the "new version" message from VS Icons will not be shown.

## 📅 Git Lens
- `gitlens.statusBar.dateFormat`: This option is currently empty, meaning you need to provide the format for dates in the GitLens status bar.

# BurpSuite Clickjacking PoC Generator

This BurpSuite extension facilitates the generation of Proof-of-Concept (PoC) code for Clickjacking vulnerabilities.

## Installation

1. Clone the repository

```
git clone https://github.com/alpernae/GenerateClickJackingPoC
```

2. Open BurpSuite.
3. Navigate to the "Extender" tab.
4. Click on the "Extensions" sub-tab.
5. Click on the "Add" button.
6. Choose "Python" as the extension type.
7. Select the `generateClickJackingPoC.py` file.
8. The extension should now be loaded successfully.

## Usage

1. Highlight an HTTP message in BurpSuite.
2. Right-click to open the context menu.
3. Select "Generate Clickjacking PoC".
4. A dialog box will appear with the generated Clickjacking PoC HTML code.
5. You can copy the code to the clipboard or close the dialog box.

## Disclaimer

This extension is provided for educational purposes only. Use it responsibly and only on systems you are authorized to test.


# mcm-lyx

LyX template for COMAP's Mathematical Contest in Modeling (MCM)

## Project structure

- `_template.lyx`: A template with preset document properties. All of our new files should start here.
- `1911426.lyx`: The main LyX file includes all other sub-documents. 1911426 is our team's control number. Feel free to rename it to your own control number.
- `01_first_page.lyx` The first page, including Title and Summary.
- `02_...`
- `...` Sub-documents, with a self-explained name. They are all included in `1911426.lyx`.
- `10_appendices.lyx`

## Tips

<!-- 使用 vscode 为 `.lyx` 增加代码高亮和自动补全：

![vscode-lyx](docs/images/vscode-lyx.gif) -->

### All in one editor

Keep all sub-documents and the main LyX file in one editor window, in this way, you will have 3 advantages:

1. The sub-documents will be able to cite the references defined by the `.bib` file which is included in the main LyX file.
2. Also, the sub-documents' Section number will show up correctly.
3. You don't need to save the sub-documents before you compile all the documents. Just click the first eye or use <kbd>Ctrl</kbd>+<kbd>R</kbd> to compile the main document is okay.

![all-in-one](docs/images/all-in-one.gif)

### Math shortcut

Use shortcut <kbd>Ctrl</kbd>+<kbd>M</kbd> to enter math mode, where you can write math equations using TeX syntax with `Tab` for auto-completing.

![raw-math](docs/images/raw-math.gif)

### Useful shortcuts

<center>

|           Shortcut           | Function |
| :--------------------------: | :------: |
| <kbd>Ctrl</kbd>+<kbd>R</kbd> |   View   |
| <kbd>Ctrl</kbd>+<kbd>M</kbd> | Math|
| <kbd>Alt</kbd>+<kbd>P</kbd>, <kbd>B</kbd> | Itemized list|
| <kbd>Alt</kbd>+<kbd>P</kbd>, <kbd>E</kbd> | Numbered list|
| <kbd>Alt</kbd>+<kbd>A</kbd>, <kbd>L/C/R</kbd> | Align Left/Center/Right|

</center>
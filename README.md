## Auto PDF Mark
### Description
A simple java-based tool that could generate the PDF bookmarks from the link in the file. If a word is linked from other section in the file, it is probably a header. The headers are now used as bookmarks, which enable user to move quickly in any PDF reader.

### Execution
#### Run
`$ java -jar auto-pdf-mark.jar [input.pdf] [output.pdf]`

### Other PDF Mark Method
Use Nitro, See https://www.gonitro.com/user-guide/pro/article/create-bookmarks-automatically. Set level1 mask:
`^[1-9][.] `
level2 mask:
`^[1-9][.][1-9] `
level3 to level5

### Optimize
Use PDFPatcher to edit chapter bookmark menu level.

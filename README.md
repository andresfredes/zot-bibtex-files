# zot-bibtex-files
Zotero Export Translators for:
- BibTeX, with hierarchical file export matching library/collection structure
- EndNote XML, with additional keywords matching item collections

## Description
### BibTeXFiles.js
- Exports references to BibTex (thanks to https://github.com/zotero/translators/blob/master/BibTeX.js)
- Exports files to hierarchical structure mirroring library collections/subcollections (thanks to https://github.com/retorquere/zotero-file-hierarchy/)
- Adds tags to each reference for each ancestor collection within library

### TaggedEndNodeXML.js
- Exports references to EndNote XML (thanks to https://github.com/zotero/translators/blob/master/Endnote%20XML.js)  
- Adds tags to each reference for each ancestor collection within library

## Usage
Copy the two `.js` files into Zotero/translators/ then restart Zotero

"BibTeX and Files" and "EndNote XML with Tags" will now appear as options in the Export Library dialog box

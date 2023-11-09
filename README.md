# zotero-better-plugin

Make zotero7 plugins better, including note templates, tag actions, etc.

## zotero7 recommended plugins

- [zotero-addons](https://github.com/syt2/zotero-addons)
- [zotero-pdf-translate](https://github.com/windingwind/zotero-pdf-translate)
- [zotero-better-notes](https://github.com/windingwind/zotero-better-notes)
- [zotero-better-bibtex](https://github.com/retorquere/zotero-better-bibtex)
- [jasminum](https://github.com/l0o0/jasminum)
- [zotero-gpt](https://github.com/MuiseDestiny/zotero-gpt)
- [zotero-style](https://github.com/MuiseDestiny/zotero-style)
- [zotero-night](https://github.com/tefkah/zotero-night)
- [zotero-actions-tags](https://github.com/windingwind/zotero-actions-tags)
- [zotero-reference](https://github.com/MuiseDestiny/zotero-reference)
- [zotero-pdf-preview](https://github.com/windingwind/zotero-pdf-preview)
- [zotero-format-metadata](https://github.com/northword/zotero-format-metadata)
- [zotero-citation](https://github.com/MuiseDestiny/zotero-citation)
- [zotero-figure](https://github.com/MuiseDestiny/zotero-figure)
- [delitemwithatt](https://github.com/redleafnew/delitemwithatt)
- [notero](https://github.com/dvanoni/notero)

## zotero-better-notes

[Note Discussions](https://github.com/windingwind/zotero-better-notes/discussions)

### Note Templates

- [Paper Note](./zotero-better-notes/[Item]PaperNote.md)
  ![Paper Note](./imgs/PaperNote.png)
  - `MetaData` : Auto extract Author, Journal, Journal Tags, Local Link, DOI, Abstract, Note Date, etc.
  - `DOI` : Show `url` if the DOI does not exist.
  - `Abstract` : Show `abstractTranslation` if the it exists. Otherwise, show `abstractNote`.

- [Main Note](./zotero-better-notes/[Text]MainNote.md)
  ![Main Note](./imgs/MainNote.png)

- [Common Note](./zotero-better-notes/[Text]CommonNote.md)

## zotero-actions-tags

[Actions & Tags Discussions](https://github.com/windingwind/zotero-actions-tags/discussions)

### Actions

- [Toggle Left Pane](./zotero-actions-tags/ToggleLeftPane)
  - `Name` : Toggle Left Pane
  - `Event` : None
  - `Operation` : Script
  - `Data` : `ToggleLeftPane`
  - `Shortcut`: Shift + [

- [Toggle Right Pane](./zotero-actions-tags/ToggleRightPane)
  - `Name` : Toggle Right Pane
  - `Event` : None
  - `Operation` : Script
  - `Data` : `ToggleRightPane`
  - `Shortcut`: Shift + ]

- [New Paper Note](./zotero-actions-tags/NewPaperNote)
  - `Name` : New Paper Note
  - `Event` : None
  - `Operation` : Script
  - `Data` : `NewPaperNote`
  - `Shortcut`: None
  - `Menu Label`: New Paper Note

- [New Common Note](./zotero-actions-tags/NewCommonNote)
  - `Name` : New Common Note
  - `Event` : None
  - `Operation` : Script
  - `Data` : `NewCommonNote`
  - `Shortcut`: None
  - `Menu Label`: New Common Note

- [Copy Item Link](./zotero-actions-tags/CopyItemLink)
  - `Name` : Copy Item Link
  - `Event` : None
  - `Operation` : Script
  - `Data` : `CopyItemLink`
  - `Shortcut`: None
  - `Menu Label`: Copy Item Link

- [Merge Duplicate Item](./zotero-actions-tags/MergeDupItem)
  - `Name` : Merge Duplicate Item
  - `Event` : None
  - `Operation` : Script
  - `Data` : `MergeDupItem`
  - `Shortcut`: None
  - `Menu Label`: Merge Duplicate Item

- [Download PDF from Scihub](./zotero-actions-tags/PDFFromScihub)
  - `Name` : Download PDF From Scihub
  - `Event` : None
  - `Operation` : Script
  - `Data` : `PDFFromScihub`
  - `Shortcut`: None
  - `Menu Label`: Download PDF From Scihub

## zotero-gpt

[Command Tags Discussions](https://github.com/MuiseDestiny/zotero-gpt/discussions)

### Command Tag

- [期刊评价](./zotero-gpt/JournalEvaluation)

- [方法总结](./zotero-gpt/MethodSummary)

- [创新点](./zotero-gpt/Innovation)

- [摘要转综述](./zotero-gpt/AbstractToReview)

- [数学公式解释](./zotero-gpt/MathSolver)

# zotero-better-plugin

Make zotero7 plugins better, including note templates, tag actions, etc.

## zotero-better-notes

### Note Templates

- [Paper Note](./zotero-better-notes/[Item]PaperNote)
  ![Paper Note](./imgs/PaperNote.png)
  - `MetaData` : Auto extract Author, Journal, Journal Division, Local Link, DOI, Abstract, Note Date, etc.
  - `DOI` : Show `yrl` if the DOI does not exist.
  - `Abstract` : Show `abstractTranslation` if the it exists. Otherwise, show `abstractNote`.

- [Main Note](./zotero-better-notes/[Text]MainNote)
  ![Main Note](./imgs/MainNote.png)

- [Common Note](./zotero-better-notes/[Text]CommonNote)

## zotero-actions-tags

### Actions

- [Toggle Left Pane](./zotero-actions-tags/ToggleLeftPane)
  - `Event` : None
  - `Operation` : Script
  - `Data` : `ToggleLeftPane`
  - `Shortcut`: Shift + [

- [Toggle Right Pane](./zotero-actions-tags/ToggleRightPane)
  - `Event` : None
  - `Operation` : Script
  - `Data` : `ToggleRightPane`
  - `Shortcut`: Shift + ]

---
title: Editors
---

* [Editor basics tutorial](/tutorials/editor_basics.md)
* [Multiple carets](multiple_carets.md)

## Editor Customization

* **Custom Title** (e.g. `plugin.xml (my-plugin)`): see `com.intellij.openapi.fileEditor.impl.EditorTabTitleProvider`
* **Custom Icon** see `com.intellij.ide.IconProvider` (PSI), `com.intellij.ide.FileIconProvider` (VFS),  `com.intellij.util.IconUtil`
* **Custom Icon (Overlay)** see `com.intellij.ide.FileIconPatcher`, `com.intellij.ide.IconLayerProvider`

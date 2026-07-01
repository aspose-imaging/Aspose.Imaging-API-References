---
title: "EmfPlusPalette"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusPalette يحدد الألوان التي تشكل لوحة ألوان."
type: docs
weight: 57
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPalette extends EmfPlusStructureObjectType
```

كائن EmfPlusPalette يحدد الألوان التي تشكل لوحة ألوان.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusPalette()](#EmfPlusPalette--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPaletteStyleFlags()](#getPaletteStyleFlags--) | يحصل أو يعيّن علامات نمط اللوحة. |
| [setPaletteStyleFlags(int value)](#setPaletteStyleFlags-int-) | يحصل أو يعيّن علامات نمط اللوحة. |
| [getArgb32Entries()](#getArgb32Entries--) | يحصل أو يعيّن مدخلات اللوحة. |
| [setArgb32Entries(int[] value)](#setArgb32Entries-int---) | يحصل أو يعيّن مدخلات اللوحة. |
### EmfPlusPalette() {#EmfPlusPalette--}
```
public EmfPlusPalette()
```


### getPaletteStyleFlags() {#getPaletteStyleFlags--}
```
public int getPaletteStyleFlags()
```


يحصل أو يعيّن علامات نمط اللوحة.

القيمة: PaletteStyleFlags (4 بايت): عدد صحيح غير موقّع 32‑بت يحدد سمات البيانات في اللوحة. يجب أن تتكوّن هذه القيمة من أعلام `EmfPlusPaletteStyleFlags`.

**Returns:**
int
### setPaletteStyleFlags(int value) {#setPaletteStyleFlags-int-}
```
public void setPaletteStyleFlags(int value)
```


يحصل أو يعيّن علامات نمط اللوحة.

القيمة: PaletteStyleFlags (4 بايت): عدد صحيح غير موقّع 32‑بت يحدد سمات البيانات في اللوحة. يجب أن تتكوّن هذه القيمة من أعلام `EmfPlusPaletteStyleFlags`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


يحصل أو يعيّن مدخلات اللوحة.

القيمة: PaletteEntries (متغيّر): مصفوفة من كائنات ARGB 32‑بت عددها PaletteCount تحدد البيانات في اللوحة.

**Returns:**
int[] - نسخة من مدخلات اللوحة.
### setArgb32Entries(int[] value) {#setArgb32Entries-int---}
```
public void setArgb32Entries(int[] value)
```


يحصل أو يعيّن مدخلات اللوحة.

القيمة: PaletteEntries (متغيّر): مصفوفة من كائنات ARGB 32‑بت عددها PaletteCount تحدد البيانات في اللوحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] |  |


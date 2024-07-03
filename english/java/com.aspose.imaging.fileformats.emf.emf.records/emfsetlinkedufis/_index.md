---
title: EmfSetLinkedUfis
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETLINKEDUFIS record sets the UniversalFontIds section 2.2.27 of the linked fonts to use during character lookup.
type: docs
weight: 129
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfsetlinkedufis/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetLinkedUfis extends EmfStateRecordType
```

The EMR\_SETLINKEDUFIS record sets the UniversalFontIds (section 2.2.27) of the linked fonts to use during character lookup.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetLinkedUfis(EmfRecord source)](#EmfSetLinkedUfis-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetLinkedUfis` class. |
## Methods

| Method | Description |
| --- | --- |
| [getUfis()](#getUfis--) | Gets an array of uNumLinkedUFI elements of type UniversalFontId, which specifies the identifiers of the linked fonts. |
| [setUfis(EmfUniversalFontId[] value)](#setUfis-com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId---) | Sets an array of uNumLinkedUFI elements of type UniversalFontId, which specifies the identifiers of the linked fonts. |
### EmfSetLinkedUfis(EmfRecord source) {#EmfSetLinkedUfis-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetLinkedUfis(EmfRecord source)
```


Initializes a new instance of the `EmfSetLinkedUfis` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getUfis() {#getUfis--}
```
public EmfUniversalFontId[] getUfis()
```


Gets an array of uNumLinkedUFI elements of type UniversalFontId, which specifies the identifiers of the linked fonts.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId[]
### setUfis(EmfUniversalFontId[] value) {#setUfis-com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId---}
```
public void setUfis(EmfUniversalFontId[] value)
```


Sets an array of uNumLinkedUFI elements of type UniversalFontId, which specifies the identifiers of the linked fonts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfUniversalFontId\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid) |  |


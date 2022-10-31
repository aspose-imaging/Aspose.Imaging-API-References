---
title: EmfSetTextAlign
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETTEXTALIGN record specifies text alignment.
type: docs
weight: 136
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextAlign extends EmfStateRecordType
```

The EMR\_SETTEXTALIGN record specifies text alignment.

The EMR\_SMALLTEXTOUT, EMR\_EXTTEXTOUTA, and EMR\_EXTTEXTOUTW records use text alignment values to position a string of text on the output medium. The values specify the relationship between a reference point and a rectangle that bounds the text. The reference point is either the current position or a point passed to a text output record. The rectangle that bounds the text is formed by the character cells in the text string.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetTextAlign(EmfRecord source)](#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetTextAlign` class. |
| [EmfSetTextAlign()](#EmfSetTextAlign--) | Initializes a new instance of the `EmfSetTextAlign` class. |
## Methods

| Method | Description |
| --- | --- |
| [getTextAlignmentMode()](#getTextAlignmentMode--) | Gets or sets a 32-bit unsigned integer that specifies text alignment by using a mask of text alignment flags. |
| [setTextAlignmentMode(int value)](#setTextAlignmentMode-int-) | Gets or sets a 32-bit unsigned integer that specifies text alignment by using a mask of text alignment flags. |
### EmfSetTextAlign(EmfRecord source) {#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextAlign(EmfRecord source)
```


Initializes a new instance of the `EmfSetTextAlign` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetTextAlign() {#EmfSetTextAlign--}
```
public EmfSetTextAlign()
```


Initializes a new instance of the `EmfSetTextAlign` class.

### getTextAlignmentMode() {#getTextAlignmentMode--}
```
public int getTextAlignmentMode()
```


Gets or sets a 32-bit unsigned integer that specifies text alignment by using a mask of text alignment flags. These are either `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] section 2.1.2.3) for text with a horizontal baseline, or `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] section 2.1.2.4) for text with a vertical baseline. Only one value can be chosen from those that affect horizontal and vertical alignment.

**Returns:**
int
### setTextAlignmentMode(int value) {#setTextAlignmentMode-int-}
```
public void setTextAlignmentMode(int value)
```


Gets or sets a 32-bit unsigned integer that specifies text alignment by using a mask of text alignment flags. These are either `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] section 2.1.2.3) for text with a horizontal baseline, or `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] section 2.1.2.4) for text with a vertical baseline. Only one value can be chosen from those that affect horizontal and vertical alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |


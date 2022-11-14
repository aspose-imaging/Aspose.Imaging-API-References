---
title: EmfPlusHeader
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusHeader record specifies the start of EMF data in the metafile.
type: docs
weight: 40
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusHeader extends EmfPlusControlRecordType
```

The EmfPlusHeader record specifies the start of EMF+ data in the metafile. The EmfPlusHeader record MUST be embedded in an EMF EMR\_COMMENT\_EMFPLUS record, which MUST be the record immediately following the EMF header in the metafile. The EMR\_COMMENT\_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusHeader(EmfPlusRecord source)](#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusHeader` class. |
## Methods

| Method | Description |
| --- | --- |
| [getDualMode()](#getDualMode--) | Gets or sets a value indicating whether [dual mode]. |
| [setDualMode(boolean value)](#setDualMode-boolean-) | Gets or sets a value indicating whether [dual mode]. |
| [getVideoDisplay()](#getVideoDisplay--) | Gets or sets a value indicating whether video display. |
| [setVideoDisplay(boolean value)](#setVideoDisplay-boolean-) | Gets or sets a value indicating whether video display. |
| [getEmfPlusFlags()](#getEmfPlusFlags--) | Gets or sets the EMF plus flags. |
| [setEmfPlusFlags(int value)](#setEmfPlusFlags-int-) | Gets or sets the EMF plus flags. |
| [getLogicalDpiX()](#getLogicalDpiX--) | Gets or sets the logical dpi x. |
| [setLogicalDpiX(int value)](#setLogicalDpiX-int-) | Gets or sets the logical dpi x. |
| [getLogicalDpiY()](#getLogicalDpiY--) | Gets or sets the logical dpi y. |
| [setLogicalDpiY(int value)](#setLogicalDpiY-int-) | Gets or sets the logical dpi y. |
| [getVersion()](#getVersion--) | Gets or sets the version. |
| [setVersion(EmfPlusGraphicsVersion value)](#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-) | Gets or sets the version. |
| [isValid()](#isValid--) | Gets a value indicating whether this instance is valid. |
### EmfPlusHeader(EmfPlusRecord source) {#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusHeader(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusHeader` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getDualMode() {#getDualMode--}
```
public boolean getDualMode()
```


Gets or sets a value indicating whether [dual mode]. If set, this flag indicates that this metafile is "dual-mode", which means that it contains two sets of records, each of which completely specifies the graphics content. If clear, the graphics content is specified by EMF+ records, and possibly EMF records that are preceded by an EmfPlusGetDC record. If this flag is set, EMF records alone SHOULD suffice to define the graphics content. Note that whether the "dual-mode" flag is set or not, some EMF records are always present, namely EMF control records and the EMF records that contain EMF+ records. EMF control records are specified in [MS-EMF] section 2.3.4.

Value: `true` if [dual mode]; otherwise, `false`.

**Returns:**
boolean
### setDualMode(boolean value) {#setDualMode-boolean-}
```
public void setDualMode(boolean value)
```


Gets or sets a value indicating whether [dual mode]. If set, this flag indicates that this metafile is "dual-mode", which means that it contains two sets of records, each of which completely specifies the graphics content. If clear, the graphics content is specified by EMF+ records, and possibly EMF records that are preceded by an EmfPlusGetDC record. If this flag is set, EMF records alone SHOULD suffice to define the graphics content. Note that whether the "dual-mode" flag is set or not, some EMF records are always present, namely EMF control records and the EMF records that contain EMF+ records. EMF control records are specified in [MS-EMF] section 2.3.4.

Value: `true` if [dual mode]; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVideoDisplay() {#getVideoDisplay--}
```
public boolean getVideoDisplay()
```


Gets or sets a value indicating whether video display. if set, this flag indicates that the metafile was recorded with a reference device context for a video display. If clear, the metafile was recorded with a reference device context for a printer.

Value: `true` if [video display]; otherwise, `false`.

**Returns:**
boolean
### setVideoDisplay(boolean value) {#setVideoDisplay-boolean-}
```
public void setVideoDisplay(boolean value)
```


Gets or sets a value indicating whether video display. if set, this flag indicates that the metafile was recorded with a reference device context for a video display. If clear, the metafile was recorded with a reference device context for a printer.

Value: `true` if [video display]; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmfPlusFlags() {#getEmfPlusFlags--}
```
public int getEmfPlusFlags()
```


Gets or sets the EMF plus flags. A 32-bit unsigned integer that contains information about how this metafile was recorded. if 31-st bit of the field is set, this flag indicates that the metafile was recorded with a reference device context for a video display. If clear, the metafile was recorded with a reference device context for a printer.

Value: The EMF plus flags.

**Returns:**
int
### setEmfPlusFlags(int value) {#setEmfPlusFlags-int-}
```
public void setEmfPlusFlags(int value)
```


Gets or sets the EMF plus flags. A 32-bit unsigned integer that contains information about how this metafile was recorded. if 31-st bit of the field is set, this flag indicates that the metafile was recorded with a reference device context for a video display. If clear, the metafile was recorded with a reference device context for a printer.

Value: The EMF plus flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLogicalDpiX() {#getLogicalDpiX--}
```
public int getLogicalDpiX()
```


Gets or sets the logical dpi x. A 32-bit unsigned integer that specifies the horizontal resolution for which the metafile was recorded, in units of pixels per inch.

Value: The logical dpi x.

**Returns:**
int
### setLogicalDpiX(int value) {#setLogicalDpiX-int-}
```
public void setLogicalDpiX(int value)
```


Gets or sets the logical dpi x. A 32-bit unsigned integer that specifies the horizontal resolution for which the metafile was recorded, in units of pixels per inch.

Value: The logical dpi x.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLogicalDpiY() {#getLogicalDpiY--}
```
public int getLogicalDpiY()
```


Gets or sets the logical dpi y. A 32-bit unsigned integer that specifies the vertical resolution for which the metafile was recorded, in units of lines per inch

Value: The logical dpi y.

**Returns:**
int
### setLogicalDpiY(int value) {#setLogicalDpiY-int-}
```
public void setLogicalDpiY(int value)
```


Gets or sets the logical dpi y. A 32-bit unsigned integer that specifies the vertical resolution for which the metafile was recorded, in units of lines per inch

Value: The logical dpi y.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public EmfPlusGraphicsVersion getVersion()
```


Gets or sets the version. An EmfPlusGraphicsVersion object (section 2.2.2.19) that specifies the version of operating system graphics that was used to create this metafile.

Value: The version.

**Returns:**
[EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion)
### setVersion(EmfPlusGraphicsVersion value) {#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-}
```
public void setVersion(EmfPlusGraphicsVersion value)
```


Gets or sets the version. An EmfPlusGraphicsVersion object (section 2.2.2.19) that specifies the version of operating system graphics that was used to create this metafile.

Value: The version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion) |  |

### isValid() {#isValid--}
```
public boolean isValid()
```


Gets a value indicating whether this instance is valid.

Value: `true` if this instance is valid; otherwise, `false`.

**Returns:**
boolean

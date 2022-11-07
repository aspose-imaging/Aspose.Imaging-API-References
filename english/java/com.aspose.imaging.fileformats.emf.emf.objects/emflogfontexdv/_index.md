---
title: EmfLogFontExDv
second_title: Aspose.Imaging for Java API Reference
description: The LogFontExDv object specifies the design vector for an extended logical font.
type: docs
weight: 24
url: /java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfontexdv/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFontEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfontex)
```
public final class EmfLogFontExDv extends EmfLogFontEx
```

The LogFontExDv object specifies the design vector for an extended logical font.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfLogFontExDv(EmfLogFontEx emfLogFontEx)](#EmfLogFontExDv-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFontEx-) | Initializes a new instance of the `EmfLogFontExDv` class. |
## Methods

| Method | Description |
| --- | --- |
| [getDesignVector()](#getDesignVector--) | Gets or sets a DesignVector object (section 2.2.3). |
| [setDesignVector(EmfDesignVector value)](#setDesignVector-com.aspose.imaging.fileformats.emf.emf.objects.EmfDesignVector-) | Gets or sets a DesignVector object (section 2.2.3). |
### EmfLogFontExDv(EmfLogFontEx emfLogFontEx) {#EmfLogFontExDv-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFontEx-}
```
public EmfLogFontExDv(EmfLogFontEx emfLogFontEx)
```


Initializes a new instance of the `EmfLogFontExDv` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| emfLogFontEx | [EmfLogFontEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfontex) | The EMF log font ex. |

### getDesignVector() {#getDesignVector--}
```
public EmfDesignVector getDesignVector()
```


Gets or sets a DesignVector object (section 2.2.3). This field MUST NOT be longer than 72 bytes.

Value: The design vector.

**Returns:**
[EmfDesignVector](../../com.aspose.imaging.fileformats.emf.emf.objects/emfdesignvector)
### setDesignVector(EmfDesignVector value) {#setDesignVector-com.aspose.imaging.fileformats.emf.emf.objects.EmfDesignVector-}
```
public void setDesignVector(EmfDesignVector value)
```


Gets or sets a DesignVector object (section 2.2.3). This field MUST NOT be longer than 72 bytes.

Value: The design vector.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfDesignVector](../../com.aspose.imaging.fileformats.emf.emf.objects/emfdesignvector) |  |


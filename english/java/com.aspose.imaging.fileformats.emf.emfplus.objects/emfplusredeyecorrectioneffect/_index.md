---
title: EmfPlusRedEyeCorrectionEffect
second_title: Aspose.Imaging for Java API Reference
description: The RedEyeCorrectionEffect object specifies areas of an image to which a red-eye correction is applied.
type: docs
weight: 67
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusredeyecorrectioneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusRedEyeCorrectionEffect extends EmfPlusImageEffectsObjectType
```

The RedEyeCorrectionEffect object specifies areas of an image to which a red-eye correction is applied.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusRedEyeCorrectionEffect()](#EmfPlusRedEyeCorrectionEffect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getNumberOfAreas()](#getNumberOfAreas--) | Gets or sets the A 32-bit signed integer that specifies the number of rectangles in the Areas field. |
| [setNumberOfAreas(int value)](#setNumberOfAreas-int-) | Gets or sets the A 32-bit signed integer that specifies the number of rectangles in the Areas field. |
| [getAreas()](#getAreas--) | Gets or sets the An array of NumberOfAreas WMF RectL objects, specified in [MS-WMF] section 2.2.2.19. |
| [setAreas(Rectangle[] value)](#setAreas-com.aspose.imaging.Rectangle---) | Gets or sets the An array of NumberOfAreas WMF RectL objects, specified in [MS-WMF] section 2.2.2.19. |
### EmfPlusRedEyeCorrectionEffect() {#EmfPlusRedEyeCorrectionEffect--}
```
public EmfPlusRedEyeCorrectionEffect()
```


### getNumberOfAreas() {#getNumberOfAreas--}
```
public int getNumberOfAreas()
```


Gets or sets the A 32-bit signed integer that specifies the number of rectangles in the Areas field.

Value: The number of areas.

**Returns:**
int
### setNumberOfAreas(int value) {#setNumberOfAreas-int-}
```
public void setNumberOfAreas(int value)
```


Gets or sets the A 32-bit signed integer that specifies the number of rectangles in the Areas field.

Value: The number of areas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAreas() {#getAreas--}
```
public Rectangle[] getAreas()
```


Gets or sets the An array of NumberOfAreas WMF RectL objects, specified in [MS-WMF] section 2.2.2.19. Each rectangle specifies an area of the bitmap image to which the red-eye correction effect SHOULD be applied.

Value: The areas.

**Returns:**
com.aspose.imaging.Rectangle[]
### setAreas(Rectangle[] value) {#setAreas-com.aspose.imaging.Rectangle---}
```
public void setAreas(Rectangle[] value)
```


Gets or sets the An array of NumberOfAreas WMF RectL objects, specified in [MS-WMF] section 2.2.2.19. Each rectangle specifies an area of the bitmap image to which the red-eye correction effect SHOULD be applied.

Value: The areas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |


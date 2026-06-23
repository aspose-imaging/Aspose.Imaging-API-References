---
title: "WmfRasterizationOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات تحويل Wmf إلى نقطية."
type: docs
weight: 55
url: /ar/java/com.aspose.imaging.imageoptions/wmfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class WmfRasterizationOptions extends MetafileRasterizationOptions
```

خيارات تحويل Wmf إلى نقطية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions--) | ينشئ مثيلًا جديدًا من الفئة `WmfRasterizationOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | يحصل أو يضبط وضعية عرض WMF. |
| [setRenderMode(int value)](#setRenderMode-int-) | يحصل أو يضبط وضعية عرض WMF. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | ينسخ هذا إلى `vectorRasterizationOptions`. |
### WmfRasterizationOptions() {#WmfRasterizationOptions--}
```
public WmfRasterizationOptions()
```


ينشئ مثيلًا جديدًا من الفئة `WmfRasterizationOptions`.

### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


يحصل أو يضبط وضعية عرض WMF.

القيمة: وضعية عرض WMF.

**Returns:**
int
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


يحصل أو يضبط وضعية عرض WMF.

القيمة: وضعية عرض WMF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // سيتم تحويل النص إلى أشكال.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // لون الخلفية لسطح الرسم.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // حجم الصفحة.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


ينسخ هذا إلى `vectorRasterizationOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |


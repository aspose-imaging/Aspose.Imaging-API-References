---
title: "EmfRasterizationOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات تحويل Emf إلى نقطية."
type: docs
weight: 20
url: /ar/java/com.aspose.imaging.imageoptions/emfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class EmfRasterizationOptions extends MetafileRasterizationOptions
```

خيارات تحويل Emf إلى نقطية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | يحصل أو يضبط وضع العرض. |
| [setRenderMode(int value)](#setRenderMode-int-) | يحصل أو يضبط وضع العرض. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | ينسخ هذا إلى `vectorRasterizationOptions`. |
### EmfRasterizationOptions() {#EmfRasterizationOptions--}
```
public EmfRasterizationOptions()
```


### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


يحصل أو يضبط وضع العرض.

**Returns:**
int - وضع العرض.
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


يحصل أو يضبط وضع العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وضع العرض. |


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // سيتم تحويل النص إلى أشكال.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // لون الخلفية لسطح الرسم.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // حجم الصفحة.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // حدد الهامش الأفقي
    rasterizationOptions.setBorderX(50);

    // حدد الهامش الرأسي
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
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


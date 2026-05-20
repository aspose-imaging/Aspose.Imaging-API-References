---
title: "RawDataSettings"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "إعدادات البيانات الخام"
type: docs
weight: 92
url: /ar/java/com.aspose.imaging/rawdatasettings/
---
**Inheritance:**
java.lang.Object
```
public class RawDataSettings
```

إعدادات البيانات الخام
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [RawDataSettings()](#RawDataSettings--) | تم تهيئة نسخة فارغة. |
| [RawDataSettings(RawDataSettings origin)](#RawDataSettings-com.aspose.imaging.RawDataSettings-) | تهيئة نسخة من `origin`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPixelDataFormat()](#getPixelDataFormat--) | يحصل على تنسيق بيانات البكسل |
| [setPixelDataFormat(PixelDataFormat value)](#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-) | يضبط تنسيق بيانات البكسل |
| [getColorPalette()](#getColorPalette--) | يحصل على لوحة الألوان |
| [setColorPalette(IColorPalette value)](#setColorPalette-com.aspose.imaging.IColorPalette-) | يضبط لوحة الألوان |
| [getDitheringMethod()](#getDitheringMethod--) | يحصل على طريقة التمويه المستخدمة لتحويل البيانات الخام |
| [setDitheringMethod(int value)](#setDitheringMethod-int-) | يضبط طريقة التمويه المستخدمة لتحويل البيانات الخام |
| [getIndexedColorConverter()](#getIndexedColorConverter--) | يحصل على محول الألوان المفهرسة |
| [setIndexedColorConverter(IIndexedColorConverter value)](#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | يضبط محول الألوان المفهرسة |
| [getCustomColorConverter()](#getCustomColorConverter--) | يحصل على محول الألوان المخصص |
| [setCustomColorConverter(IColorConverter value)](#setCustomColorConverter-com.aspose.imaging.IColorConverter-) | يضبط محول الألوان المخصص |
| [getFallbackIndex()](#getFallbackIndex--) | يحصل على الفهرس الاحتياطي لاستخدامه عندما يكون فهرس اللوحة خارج النطاق |
| [setFallbackIndex(int value)](#setFallbackIndex-int-) | يضبط الفهرس الاحتياطي لاستخدامه عندما يكون فهرس اللوحة خارج النطاق |
| [getLineSize()](#getLineSize--) | يحصل على حجم سطر البكسلات بالبايت لمعالجة البيانات الخام |
| [setLineSize(int value)](#setLineSize-int-) | يضبط حجم سطر البكسلات بالبايت لمعالجة البيانات الخام |
| [<T>copy()](#-T-copy--) | ينشئ نسخة سطحية. |
### RawDataSettings() {#RawDataSettings--}
```
public RawDataSettings()
```


تم تهيئة نسخة فارغة.

### RawDataSettings(RawDataSettings origin) {#RawDataSettings-com.aspose.imaging.RawDataSettings-}
```
public RawDataSettings(RawDataSettings origin)
```


تهيئة نسخة من `origin`. تُستخدم في [copy()](../../com.aspose.imaging/rawdatasettings\\#copy--).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| origin | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | الكائن الذي سيتم نسخ منه. |

### getPixelDataFormat() {#getPixelDataFormat--}
```
public PixelDataFormat getPixelDataFormat()
```


يحصل على تنسيق بيانات البكسل

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The pixel data format
### setPixelDataFormat(PixelDataFormat value) {#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public void setPixelDataFormat(PixelDataFormat value)
```


يضبط تنسيق بيانات البكسل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | تنسيق بيانات البكسل |

### getColorPalette() {#getColorPalette--}
```
public IColorPalette getColorPalette()
```


يحصل على لوحة الألوان

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette
### setColorPalette(IColorPalette value) {#setColorPalette-com.aspose.imaging.IColorPalette-}
```
public void setColorPalette(IColorPalette value)
```


يضبط لوحة الألوان

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان |

### getDitheringMethod() {#getDitheringMethod--}
```
public int getDitheringMethod()
```


يحصل على طريقة التمويه المستخدمة لتحويل البيانات الخام

**Returns:**
int - طريقة التمويه المستخدمة لتحويل البيانات الخام
### setDitheringMethod(int value) {#setDitheringMethod-int-}
```
public void setDitheringMethod(int value)
```


يضبط طريقة التمويه المستخدمة لتحويل البيانات الخام

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | طريقة التمويه المستخدمة لتحويل البيانات الخام |

### getIndexedColorConverter() {#getIndexedColorConverter--}
```
public IIndexedColorConverter getIndexedColorConverter()
```


يحصل على محول الألوان المفهرسة

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setIndexedColorConverter(IIndexedColorConverter value) {#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setIndexedColorConverter(IIndexedColorConverter value)
```


يضبط محول الألوان المفهرسة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | محول الألوان المفهرسة |

### getCustomColorConverter() {#getCustomColorConverter--}
```
public IColorConverter getCustomColorConverter()
```


يحصل على محول الألوان المخصص

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setCustomColorConverter(IColorConverter value) {#setCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setCustomColorConverter(IColorConverter value)
```


يضبط محول الألوان المخصص

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | محول الألوان المخصص |

### getFallbackIndex() {#getFallbackIndex--}
```
public int getFallbackIndex()
```


يحصل على الفهرس الاحتياطي لاستخدامه عندما يكون فهرس اللوحة خارج النطاق

**Returns:**
int - الفهرس الاحتياطي لاستخدامه عندما يكون فهرس اللوحة خارج النطاق
### setFallbackIndex(int value) {#setFallbackIndex-int-}
```
public void setFallbackIndex(int value)
```


يضبط الفهرس الاحتياطي لاستخدامه عندما يكون فهرس اللوحة خارج النطاق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الفهرس الاحتياطي لاستخدامه عندما يكون فهرس اللوحة خارج النطاق |

### getLineSize() {#getLineSize--}
```
public int getLineSize()
```


يحصل على حجم سطر البكسلات بالبايت لمعالجة البيانات الخام

**Returns:**
int - حجم سطر البكسلات بالبايت لمعالجة البيانات الخام
### setLineSize(int value) {#setLineSize-int-}
```
public void setLineSize(int value)
```


يضبط حجم سطر البكسلات بالبايت لمعالجة البيانات الخام

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | حجم سطر البكسلات بالبايت لمعالجة البيانات الخام |

### <T>copy() {#-T-copy--}
```
public T <T>copy()
```


ينشئ نسخة سطحية.

**Returns:**
T - نسخة سطحية.

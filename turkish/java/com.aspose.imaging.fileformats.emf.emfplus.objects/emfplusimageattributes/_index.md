---
title: "EmfPlusImageAttributes"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusImageAttributes nesnesi, bitmap görüntü renklerinin işleme sırasında nasıl manipüle edildiğini belirtir."
type: docs
weight: 48
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImageAttributes extends EmfPlusGraphicsObjectType
```

EmfPlusImageAttributes nesnesi, bitmap görüntü renklerinin işleme sırasında nasıl manipüle edildiğini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Alır veya ayarlar 32 bit işaretsiz tamsayı; bu, WrapMode numaralandırmasından bir değerle kenar koşullarının nasıl ele alınacağını belirtir (bölüm 2.1.1.34). |
| [setWrapMode(int value)](#setWrapMode-int-) | Alır veya ayarlar 32 bit işaretsiz tamsayı; bu, WrapMode numaralandırmasından bir değerle kenar koşullarının nasıl ele alınacağını belirtir (bölüm 2.1.1.34). |
| [getClampArgb32Color()](#getClampArgb32Color--) | Alır veya ayarlar EmfPlusARGB (bölüm 2.2.2.1) nesnesi; bu, WrapMode değeri WrapModeClamp olduğunda kullanılacak kenar rengini belirtir. |
| [setClampArgb32Color(int value)](#setClampArgb32Color-int-) | Alır veya ayarlar EmfPlusARGB (bölüm 2.2.2.1) nesnesi; bu, WrapMode değeri WrapModeClamp olduğunda kullanılacak kenar rengini belirtir. |
| [getObjectClamp()](#getObjectClamp--) | Alır veya ayarlar 32 bit işaretli tamsayı; bu, nesne sıkıştırma davranışını belirtir. |
| [setObjectClamp(int value)](#setObjectClamp-int-) | Alır veya ayarlar 32 bit işaretli tamsayı; bu, nesne sıkıştırma davranışını belirtir. |
### EmfPlusImageAttributes() {#EmfPlusImageAttributes--}
```
public EmfPlusImageAttributes()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Alır veya ayarlar 32 bit işaretsiz tamsayı; bu, WrapMode numaralandırmasından bir değerle kenar koşullarının nasıl ele alınacağını belirtir (bölüm 2.1.1.34).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Alır veya ayarlar 32 bit işaretsiz tamsayı; bu, WrapMode numaralandırmasından bir değerle kenar koşullarının nasıl ele alınacağını belirtir (bölüm 2.1.1.34).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getClampArgb32Color() {#getClampArgb32Color--}
```
public int getClampArgb32Color()
```


Alır veya ayarlar EmfPlusARGB (bölüm 2.2.2.1) nesnesi; bu, WrapMode değeri WrapModeClamp olduğunda kullanılacak kenar rengini belirtir. Bu renk, bir EmfPlusDrawImage (bölüm 2.3.4.8) kaydı tarafından işlenen kaynak dikdörtgen görüntünün kendisinden daha büyük olduğunda görünür.

**Returns:**
int
### setClampArgb32Color(int value) {#setClampArgb32Color-int-}
```
public void setClampArgb32Color(int value)
```


Alır veya ayarlar EmfPlusARGB (bölüm 2.2.2.1) nesnesi; bu, WrapMode değeri WrapModeClamp olduğunda kullanılacak kenar rengini belirtir. Bu renk, bir EmfPlusDrawImage (bölüm 2.3.4.8) kaydı tarafından işlenen kaynak dikdörtgen görüntünün kendisinden daha büyük olduğunda görünür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getObjectClamp() {#getObjectClamp--}
```
public int getObjectClamp()
```


Alır veya ayarlar 32 bit işaretli tamsayı; bu, nesne sıkıştırma davranışını belirtir. Bu nesne çizilen bir görüntüye uygulanana kadar kullanılmaz. Bu değer AŞAĞIDAKİ tablo içinde tanımlanan değerlerden biri OLMAK ZORUNDADIR.

**Returns:**
int
### setObjectClamp(int value) {#setObjectClamp-int-}
```
public void setObjectClamp(int value)
```


Alır veya ayarlar 32 bit işaretli tamsayı; bu, nesne sıkıştırma davranışını belirtir. Bu nesne çizilen bir görüntüye uygulanana kadar kullanılmaz. Bu değer AŞAĞIDAKİ tablo içinde tanımlanan değerlerden biri OLMAK ZORUNDADIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |


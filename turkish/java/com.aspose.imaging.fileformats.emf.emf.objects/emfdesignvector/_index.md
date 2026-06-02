---
title: "EmfDesignVector"
second_title: "Aspose.Imaging for Java API Referansı"
description: "DesignVector bölüm 2.2.3 nesnesi, çoklu ana fontun yazı tipi eksenleri için değerleri belirten tasarım vektörünü tanımlar."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfDesignVector extends EmfObject
```

DesignVector (bölüm 2.2.3) nesnesi, çoklu ana fontun font eksenleri için değerleri belirten tasarım vektörünü tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfDesignVector()](#EmfDesignVector--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSignature()](#getSignature--) | 32 bit işaretsiz tam sayı alır veya ayarlar; bu değer 0x08007664 olmalıdır. |
| [setSignature(int value)](#setSignature-int-) | 32 bit işaretsiz tam sayı alır veya ayarlar; bu değer 0x08007664 olmalıdır. |
| [getNumAxes()](#getNumAxes--) | 32 bit işaretsiz tam sayı alır veya ayarlar; bu, Values dizisindeki öğe sayısını belirtir. |
| [setNumAxes(int value)](#setNumAxes-int-) | 32 bit işaretsiz tam sayı alır veya ayarlar; bu, Values dizisindeki öğe sayısını belirtir. |
| [getValues()](#getValues--) | 32 bit işaretli tam sayılardan oluşan isteğe bağlı bir dizi alır veya ayarlar; bu dizi, çoklu ana, OpenType yazı tipinin eksen değerlerini belirtir. |
| [setValues(int[] value)](#setValues-int---) | 32 bit işaretli tam sayılardan oluşan isteğe bağlı bir dizi alır veya ayarlar; bu dizi, çoklu ana, OpenType yazı tipinin eksen değerlerini belirtir. |
### EmfDesignVector() {#EmfDesignVector--}
```
public EmfDesignVector()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


32 bit işaretsiz tam sayı alır veya ayarlar; bu değer 0x08007664 olmalıdır.

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


32 bit işaretsiz tam sayı alır veya ayarlar; bu değer 0x08007664 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getNumAxes() {#getNumAxes--}
```
public int getNumAxes()
```


32 bit işaretsiz tam sayı alır veya ayarlar; bu, Values dizisindeki öğe sayısını belirtir. Değer 0 ile 16 arasında, uçlar dahil, olmalıdır.

**Returns:**
int
### setNumAxes(int value) {#setNumAxes-int-}
```
public void setNumAxes(int value)
```


32 bit işaretsiz tam sayı alır veya ayarlar; bu, Values dizisindeki öğe sayısını belirtir. Değer 0 ile 16 arasında, uçlar dahil, olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getValues() {#getValues--}
```
public int[] getValues()
```


32 bit işaretli tam sayılardan oluşan isteğe bağlı bir dizi alır veya ayarlar; bu dizi, çoklu ana, OpenType yazı tipinin eksen değerlerini belirtir. Dizideki maksimum değer sayısı 16'dır.

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


32 bit işaretli tam sayılardan oluşan isteğe bağlı bir dizi alır veya ayarlar; bu dizi, çoklu ana, OpenType yazı tipinin eksen değerlerini belirtir. Dizideki maksimum değer sayısı 16'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |


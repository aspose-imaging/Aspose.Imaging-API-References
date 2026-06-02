---
title: "EmfEpsData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EpsData nesnesi, EPS verileri için bir kapsayıcıdır."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfEpsData extends EmfObject
```

EpsData nesnesi, EPS verileri için bir kapsayıcıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfEpsData()](#EmfEpsData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSizeData()](#getSizeData--) | Bu nesnenin toplam boyutunu bayt cinsinden belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar |
| [setSizeData(int value)](#setSizeData-int-) | Bu nesnenin toplam boyutunu bayt cinsinden belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar |
| [getVersion()](#getVersion--) | PostScript dil seviyesini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setVersion(int value)](#setVersion-int-) | PostScript dil seviyesini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getPoints()](#getPoints--) | 28.4 bit FIX notasyonu kullanarak çıktı paralelogramının koordinatlarını tanımlayan üç Point28\_4 nesnesinden oluşan bir dizi alır veya ayarlar (bölüm 2.2.23). |
| [setPoints(EmfPoint28To4[] value)](#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---) | 28.4 bit FIX notasyonu kullanarak çıktı paralelogramının koordinatlarını tanımlayan üç Point28\_4 nesnesinden oluşan bir dizi alır veya ayarlar (bölüm 2.2.23). |
| [getPostScriptData()](#getPostScriptData--) | PostScript verisinin bayt dizisini alır veya ayarlar. |
| [setPostScriptData(byte[] value)](#setPostScriptData-byte---) | PostScript verisinin bayt dizisini alır veya ayarlar. |
### EmfEpsData() {#EmfEpsData--}
```
public EmfEpsData()
```


### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Bu nesnenin toplam boyutunu bayt cinsinden belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Bu nesnenin toplam boyutunu bayt cinsinden belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


PostScript dil seviyesini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer 0x00000001 OLMALIDIR.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


PostScript dil seviyesini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer 0x00000001 OLMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPoints() {#getPoints--}
```
public EmfPoint28To4[] getPoints()
```


28.4 bit FIX notasyonu kullanarak çıktı paralelogramının koordinatlarını tanımlayan üç Point28\_4 nesnesinden oluşan bir dizi alır veya ayarlar (bölüm 2.2.23).

Paralelogramın sol üst köşesi bu dizideki ilk noktadır, sağ üst köşesi ikinci nokta, sol alt köşesi ise üçüncü noktadır. Paralelogramın sağ alt köşesi, ilk üç nokta (A, B ve C) vektör olarak ele alınarak hesaplanır.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4[]
### setPoints(EmfPoint28To4[] value) {#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---}
```
public void setPoints(EmfPoint28To4[] value)
```


28.4 bit FIX notasyonu kullanarak çıktı paralelogramının koordinatlarını tanımlayan üç Point28\_4 nesnesinden oluşan bir dizi alır veya ayarlar (bölüm 2.2.23).

Paralelogramın sol üst köşesi bu dizideki ilk noktadır, sağ üst köşesi ikinci nokta, sol alt köşesi ise üçüncü noktadır. Paralelogramın sağ alt köşesi, ilk üç nokta (A, B ve C) vektör olarak ele alınarak hesaplanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPoint28To4\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4) |  |

### getPostScriptData() {#getPostScriptData--}
```
public byte[] getPostScriptData()
```


PostScript verisinin bayt dizisini alır veya ayarlar. Bu dizinin uzunluğu SizeData alanından hesaplanabilir. Bu veri GÖRÜNTÜ oluşturmak için kullanılabilir.

**Returns:**
byte[]
### setPostScriptData(byte[] value) {#setPostScriptData-byte---}
```
public void setPostScriptData(byte[] value)
```


PostScript verisinin bayt dizisini alır veya ayarlar. Bu dizinin uzunluğu SizeData alanından hesaplanabilir. Bu veri GÖRÜNTÜ oluşturmak için kullanılabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |


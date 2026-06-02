---
title: "EmfBlendFunction"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Kaynak ve hedef bitmap'ler için karıştırma işlemlerini belirten bir yapı."
type: docs
weight: 18
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class EmfBlendFunction extends Struct<EmfBlendFunction>
```

Kaynak ve hedef bitmap'ler için karıştırma işlemlerini belirten bir yapı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfBlendFunction()](#EmfBlendFunction--) |  |
| [EmfBlendFunction(int dwordData)](#EmfBlendFunction-int-) | `EmfBlendFunction` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBlendOperation()](#getBlendOperation--) | Karıştırma işlem kodunu alır. |
| [getBlendFlags()](#getBlendFlags--) | Karıştırma bayraklarını alır. |
| [getSrcConstantAlpha()](#getSrcConstantAlpha--) | Kaynak ve hedef bitmaplerin karışımını belirleyen alfa şeffaflığını belirten 8 bit işaretsiz tam sayıyı alır. |
| [getAlphaFormat()](#getAlphaFormat--) | Kaynak ve hedef piksellerin alfa şeffaflığına göre nasıl yorumlandığını belirten bir yapıyı alır. |
| [toInt()](#toInt--) | Bir sayının dize temsilini tam sayıya dönüştürür. |
| [CloneTo(EmfBlendFunction that)](#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
| [Clone()](#Clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)](#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
### EmfBlendFunction() {#EmfBlendFunction--}
```
public EmfBlendFunction()
```


### EmfBlendFunction(int dwordData) {#EmfBlendFunction-int-}
```
public EmfBlendFunction(int dwordData)
```


`EmfBlendFunction` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dwordData | int | dword verisi. |

### getBlendOperation() {#getBlendOperation--}
```
public byte getBlendOperation()
```


Karıştırma işlem kodunu alır. Tanımlanmış tek kaynak ve hedef karıştırma işlemi 0x00'dir; bu, kaynak bitmapin, kaynak piksellerin alfa şeffaflık değerlerine göre hedef bitmap ile birleştirilmesi ZORUNLU olduğunu belirtir. Ayrıntılar için aşağıdaki denklemlere bakın.

**Returns:**
byte
### getBlendFlags() {#getBlendFlags--}
```
public byte getBlendFlags()
```


Karıştırma bayraklarını alır. Bu değer ZORUNLU olarak 0x00 olmalı ve YOK SAYILMALI.

**Returns:**
byte
### getSrcConstantAlpha() {#getSrcConstantAlpha--}
```
public byte getSrcConstantAlpha()
```


Kaynak ve hedef bitmaplerin karışımını belirleyen alfa şeffaflığını belirten 8 bit işaretsiz tam sayıyı alır. Bu değer, tüm kaynak bitmap üzerinde ZORUNLU olarak kullanılmalıdır. Minimum alfa şeffaflık değeri, sıfır, tamamen şeffaf; maksimum değer, 0xFF, tamamen opaktır. Aslında, 0xFF değeri, piksel başına alfa değerlerinin kaynak ve hedef bitmaplerin karışımını belirlediğini gösterir. Ayrıntılar için bu bölümün ilerleyen kısmındaki denklemlere bakın.

**Returns:**
byte
### getAlphaFormat() {#getAlphaFormat--}
```
public byte getAlphaFormat()
```


Kaynak ve hedef piksellerin alfa şeffaflığına göre nasıl yorumlandığını belirten bir yapıyı alır.

**Returns:**
byte
### toInt() {#toInt--}
```
public int toInt()
```


Bir sayının dize temsilini tam sayıya dönüştürür.

**Returns:**
int - Yapının DWORD değeri.
### CloneTo(EmfBlendFunction that) {#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void CloneTo(EmfBlendFunction that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

### Clone() {#Clone--}
```
public EmfBlendFunction Clone()
```




**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2) {#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public static boolean isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |
| obj2 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

**Returns:**
boolean

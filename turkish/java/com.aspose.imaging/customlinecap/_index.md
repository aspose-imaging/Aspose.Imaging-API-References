---
title: "CustomLineCap"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Özel kullanıcı tanımlı bir çizgi ucunu kapsüller."
type: docs
weight: 35
url: /tr/java/com.aspose.imaging/customlinecap/
---
**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Özel kullanıcı tanımlı bir çizgi ucunu kapsüller.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-) | Belirtilen dış hat ve doldurma ile `CustomLineCap` sınıfının yeni bir örneğini başlatır. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-) | Belirtilen mevcut `LineCap` enum'undan, belirtilen dış hat ve doldurma ile `CustomLineCap` sınıfının yeni bir örneğini başlatır. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-) | Belirtilen mevcut `LineCap` enum'undan, belirtilen dış hat, doldurma ve iç boşluk ile `CustomLineCap` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFillPath()](#getFillPath--) | Özel kapak için doldurmayı tanımlayan nesneyi alır. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.imaging.GraphicsPath-) | Özel kapağın dolgusunu tanımlayan nesneyi ayarlar. |
| [getStrokePath()](#getStrokePath--) | Özel kapağın dış hatlarını tanımlayan nesneyi alır. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.imaging.GraphicsPath-) | Özel kapağın dış hatlarını tanımlayan nesneyi ayarlar. |
| [getStrokeJoin()](#getStrokeJoin--) | `LineJoin` sayımını alır; bu, bu `CustomLineCap` nesnesini oluşturan çizgilerin nasıl birleştirileceğini belirler. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | `LineJoin` sayımını ayarlar; bu, bu `CustomLineCap` nesnesini oluşturan çizgilerin nasıl birleştirileceğini belirler. |
| [getBaseCap()](#getBaseCap--) | `LineCap` sayımını alır; bu `CustomLineCap` bunun üzerine temellendirilir. |
| [setBaseCap(int value)](#setBaseCap-int-) | `LineCap` sayımını ayarlar; bu `CustomLineCap` bunun üzerine temellendirilir. |
| [getBaseInset()](#getBaseInset--) | Kap ile çizgi arasındaki mesafeyi alır. |
| [setBaseInset(float value)](#setBaseInset-float-) | Kap ile çizgi arasındaki mesafeyi ayarlar. |
| [getWidthScale()](#getWidthScale--) | `CustomLineCap` sınıf nesnesini, `System.Drawing.Pen` nesnesinin genişliğine göre ölçeklendirme miktarını alır. |
| [setWidthScale(float value)](#setWidthScale-float-) | `CustomLineCap` sınıf nesnesini, `System.Drawing.Pen` nesnesinin genişliğine göre ölçeklendirme miktarını ayarlar. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Bu özel kapağı oluşturan çizgilerin başlangıç ve bitişinde kullanılan kapakları ayarlar. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Bu özel kapağı oluşturan çizgilerin başlangıç ve bitişinde kullanılan kapakları alır. |
| [equals(Object o)](#equals-java.lang.Object-) | Nesnelerin eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) | Geçerli nesnenin karma kodunu al. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Belirtilen dış hat ve doldurma ile `CustomLineCap` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Özel kapağın dolgusunu tanımlayan bir `GraphicsPath` nesnesi. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Özel kapağın dış hatlarını tanımlayan bir `GraphicsPath` nesnesi. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Belirtilen mevcut `LineCap` enum'undan, belirtilen dış hat ve doldurma ile `CustomLineCap` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Özel kapağın dolgusunu tanımlayan bir `GraphicsPath` nesnesi. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Özel kapağın dış hatlarını tanımlayan bir `GraphicsPath` nesnesi. |
| baseCap | int | Özel kapağı oluşturmak için kullanılacak çizgi kapağı. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Belirtilen mevcut `LineCap` enum'undan, belirtilen dış hat, doldurma ve iç boşluk ile `CustomLineCap` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Özel kapağın dolgusunu tanımlayan bir `GraphicsPath` nesnesi. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Özel kapağın dış hatlarını tanımlayan bir `GraphicsPath` nesnesi. |
| baseCap | int | Özel kapağı oluşturmak için kullanılacak çizgi kapağı. |
| baseInset | float | Kap ile çizgi arasındaki mesafe. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Özel kapak için doldurmayı tanımlayan nesneyi alır.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the fill for the custom cap.
### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.imaging.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Özel kapağın dolgusunu tanımlayan nesneyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Özel kapağın dolgusunu tanımlayan nesne. |

### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Özel kapağın dış hatlarını tanımlayan nesneyi alır.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the outline of the custom cap.
### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.imaging.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Özel kapağın dış hatlarını tanımlayan nesneyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Özel kapağın dış hatlarını tanımlayan nesne. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


`LineJoin` sayımını alır; bu, bu `CustomLineCap` nesnesini oluşturan çizgilerin nasıl birleştirileceğini belirler.

**Returns:**
int - Bu `CustomLineCap` nesnesinin çizgileri birleştirmek için kullandığı `LineJoin` sayımı.
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


`LineJoin` sayımını ayarlar; bu, bu `CustomLineCap` nesnesini oluşturan çizgilerin nasıl birleştirileceğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `CustomLineCap` nesnesinin çizgileri birleştirmek için kullandığı `LineJoin` sayımı. |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


`LineCap` sayımını alır; bu `CustomLineCap` bunun üzerine temellendirilir.

**Returns:**
int - Bu `CustomLineCap` nesnesinin temellendiği `LineCap` sayımı.
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


`LineCap` sayımını ayarlar; bu `CustomLineCap` bunun üzerine temellendirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `CustomLineCap` nesnesinin temellendiği `LineCap` sayımı. |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Kap ile çizgi arasındaki mesafeyi alır.

**Returns:**
float - Kap başlangıcı ile satır sonu arasındaki mesafe.
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Kap ile çizgi arasındaki mesafeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Kap başlangıcı ile satır sonu arasındaki mesafe. |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


`CustomLineCap` sınıf nesnesini, `System.Drawing.Pen` nesnesinin genişliğine göre ölçeklendirme miktarını alır.

**Returns:**
float - Kapın ölçekleneceği miktar.
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


`CustomLineCap` sınıf nesnesini, `System.Drawing.Pen` nesnesinin genişliğine göre ölçeklendirme miktarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Kapın ölçekleneceği miktar. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Bu özel kapağı oluşturan çizgilerin başlangıç ve bitişinde kullanılan kapakları ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startCap | int | Bu kap içinde bir satırın başlangıcında kullanılan `LineCap` enumerasyonu. |
| endCap | int | Bu kap içinde bir satırın sonunda kullanılan `LineCap` enumerasyonu. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Bu özel kapağı oluşturan çizgilerin başlangıç ve bitişinde kullanılan kapakları alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startCap | int[] | Bu kap içinde bir satırın başlangıcında kullanılan `LineCap` enumerasyonu. |
| endCap | int[] | Bu kap içinde bir satırın sonunda kullanılan `LineCap` enumerasyonu. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Nesnelerin eşit olup olmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object | Diğer nesne. |

**Returns:**
boolean - Eşitlik karşılaştırma sonucu.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli nesnenin karma kodunu al.

**Returns:**
int - Hash kodu.

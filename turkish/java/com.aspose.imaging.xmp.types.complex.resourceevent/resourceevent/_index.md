---
title: "ResourceEvent"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Çizilmiş bir nesne için boyutları içerir."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.xmp.types.complex.resourceevent/resourceevent/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Çizilmiş bir nesne için boyutları içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Yeni bir `ResourceEvent` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAction()](#getAction--) | Eylemi alır. |
| [setAction(String value)](#setAction-java.lang.String-) | Eylemi ayarlar. |
| [getChanged()](#getChanged--) | Önceki olay geçmişinden bu yana değiştirilen kaynağın bölümlerinin noktalı virgül ile ayrılmış listesini alır. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Önceki olay geçmişinden bu yana değiştirilen kaynağın bölümlerinin noktalı virgül ile ayrılmış listesini ayarlar. |
| [getInstanceId()](#getInstanceId--) | xmpMM:InstanceId değerini alır. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | xmpMM:InstanceId değerini alır veya ayarlar. |
| [getParameters()](#getParameters--) | Eylemin ek açıklamasını alır veya ayarlar. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Eylemin ek açıklamasını alır veya ayarlar. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Yazılım ajanının adını alır veya ayarlar. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Yazılım ajanının adını alır veya ayarlar. |
| [getActionDate()](#getActionDate--) | Eylem tarihini alır veya ayarlar. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Eylem tarihini alır veya ayarlar. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP formatında içerilen dize değerini alır. |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Yeni bir `ResourceEvent` sınıfı örneği başlatır.

### getAction() {#getAction--}
```
public String getAction()
```


Eylemi alır.

Tanımlı değerler: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Yeni değerler geçmiş zaman kipinde fiil olmalıdır.

**Returns:**
java.lang.String - Eylem.
### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Eylemi ayarlar.

Tanımlı değerler: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Yeni değerler geçmiş zaman kipinde fiil olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Eylem. |

### getChanged() {#getChanged--}
```
public String getChanged()
```


Önceki olay geçmişinden bu yana değiştirilen kaynağın bölümlerinin noktalı virgül ile ayrılmış listesini alır.

**Returns:**
java.lang.String - Önceki olay geçmişinden bu yana değiştirilen kaynağın bölümlerinin noktalı virgül ile ayrılmış listesi.
### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Önceki olay geçmişinden bu yana değiştirilen kaynağın bölümlerinin noktalı virgül ile ayrılmış listesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Önceki olay geçmişinden bu yana değiştirilen kaynağın bölümlerinin noktalı virgül ile ayrılmış listesi. |

### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


xmpMM:InstanceId değerini alır.

**Returns:**
java.util.UUID - xmpMM:InstanceId değerini.
### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


xmpMM:InstanceId değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.UUID | xmpMM:InstanceId değerini. |

### getParameters() {#getParameters--}
```
public String getParameters()
```


Eylemin ek açıklamasını alır veya ayarlar.

Değer: Eylemin ek açıklaması.

**Returns:**
java.lang.String
### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Eylemin ek açıklamasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Eylemin ek açıklaması. |

### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Yazılım ajanının adını alır veya ayarlar.

**Returns:**
java.lang.String - Yazılım ajanının adı.
### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Yazılım ajanının adını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yazılım ajanının adı. |

### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Eylem tarihini alır veya ayarlar.

**Returns:**
java.util.Date - Eylem tarihi.
### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Eylem tarihini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date | Eylem tarihi. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP formatında içerilen dize değerini alır.

**Returns:**
java.lang.String - XMP biçiminde içerilen dize değerini döndürür.

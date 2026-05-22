---
title: "EmfMetafileHeaderExtension1"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfMetafileHeaderExtension1 kaydı, EMF metafile'lerine yapılan ilk uzantıda kullanılan başlık kaydıdır."
type: docs
weight: 71
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
```
public class EmfMetafileHeaderExtension1 extends EmfMetafileHeader
```

EmfMetafileHeaderExtension1 kaydı, EMF metafile'larının ilk uzantısında kullanılan başlık kaydıdır. EmfHeaderExtension1 alanının ardından kalan alanlar isteğe bağlıdır ve herhangi bir sırayla bulunabilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfMetafileHeaderExtension1(EmfMetafileHeader header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Yeni bir `EmfMetafileHeaderExtension1` sınıfı örneği başlatır. |
| [EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-) | Yeni bir `EmfMetafileHeaderExtension1` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEmfHeaderExtension1()](#getEmfHeaderExtension1--) | Metafile içindeki görüntü hakkında ek bilgi belirten bir HeaderExtension1 nesnesini alır veya ayarlar. |
| [setEmfHeaderExtension1(EmfHeaderExtension1 value)](#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-) | Metafile içindeki görüntü hakkında ek bilgi belirten bir HeaderExtension1 nesnesini alır veya ayarlar. |
| [getEmfPixelFormatBuffer()](#getEmfPixelFormatBuffer--) | EMF piksel format tanımlayıcısını içeren isteğe bağlı bir bayt dizisini alır veya ayarlar; bu dizi, EmfMetafileHeaderExtension1 kaydının sabit kısmı veya EMF açıklama dizesiyle bitişik olmak zorunda değildir. |
| [setEmfPixelFormatBuffer(byte[] value)](#setEmfPixelFormatBuffer-byte---) | EMF piksel format tanımlayıcısını içeren isteğe bağlı bir bayt dizisini alır veya ayarlar; bu dizi, EmfMetafileHeaderExtension1 kaydının sabit kısmı veya EMF açıklama dizesiyle bitişik olmak zorunda değildir. |
### EmfMetafileHeaderExtension1(EmfMetafileHeader header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeader header)
```


Yeni bir `EmfMetafileHeaderExtension1` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | Başlık. |

### EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)
```


Yeni bir `EmfMetafileHeaderExtension1` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| header | [EmfMetafileHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) | Başlık. |

### getEmfHeaderExtension1() {#getEmfHeaderExtension1--}
```
public EmfHeaderExtension1 getEmfHeaderExtension1()
```


Metafile içindeki görüntü hakkında ek bilgi belirten bir HeaderExtension1 nesnesini alır veya ayarlar.

**Returns:**
[EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1)
### setEmfHeaderExtension1(EmfHeaderExtension1 value) {#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-}
```
public void setEmfHeaderExtension1(EmfHeaderExtension1 value)
```


Metafile içindeki görüntü hakkında ek bilgi belirten bir HeaderExtension1 nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1) |  |

### getEmfPixelFormatBuffer() {#getEmfPixelFormatBuffer--}
```
public byte[] getEmfPixelFormatBuffer()
```


EMF piksel format tanımlayıcısını içeren isteğe bağlı bir bayt dizisini alır veya ayarlar; bu dizi, EmfMetafileHeaderExtension1 kaydının sabit kısmı veya EMF açıklama dizesiyle bitişik olmak zorunda değildir. Bu nedenle, bu tamponda "UndefinedSpace" olarak etiketlenen alan isteğe bağlıdır ve YOK SAYILMELİDİR.

**Returns:**
byte[]
### setEmfPixelFormatBuffer(byte[] value) {#setEmfPixelFormatBuffer-byte---}
```
public void setEmfPixelFormatBuffer(byte[] value)
```


EMF piksel format tanımlayıcısını içeren isteğe bağlı bir bayt dizisini alır veya ayarlar; bu dizi, EmfMetafileHeaderExtension1 kaydının sabit kısmı veya EMF açıklama dizesiyle bitişik olmak zorunda değildir. Bu nedenle, bu tamponda "UndefinedSpace" olarak etiketlenen alan isteğe bağlıdır ve YOK SAYILMELİDİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |


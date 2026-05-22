---
title: "EmfPlusHeader"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusHeader kaydı, metafildeki EMF verisinin başlangıcını belirtir."
type: docs
weight: 40
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusHeader extends EmfPlusControlRecordType
```

EmfPlusHeader kaydı, metafildeki EMF+ verisinin başlangıcını belirtir. EmfPlusHeader kaydı, bir EMF EMR\\_COMMENT\\_EMFPLUS kaydına gömülmelidir; bu kayıt, metafildeki EMF başlığını hemen izleyen kayıt olmalıdır. EMR\\_COMMENT\\_EMFPLUS kaydı, [MS-EMF] bölüm 2.3.3.2'de belirtilmiştir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusHeader(EmfPlusRecord source)](#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusHeader` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDualMode()](#getDualMode--) | [dual mode] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setDualMode(boolean value)](#setDualMode-boolean-) | [dual mode] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getVideoDisplay()](#getVideoDisplay--) | video görüntüleme olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setVideoDisplay(boolean value)](#setVideoDisplay-boolean-) | video görüntüleme olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getEmfPlusFlags()](#getEmfPlusFlags--) | EMF plus bayraklarını alır veya ayarlar. |
| [setEmfPlusFlags(int value)](#setEmfPlusFlags-int-) | EMF plus bayraklarını alır veya ayarlar. |
| [getLogicalDpiX()](#getLogicalDpiX--) | mantıksal dpi x'i alır veya ayarlar. |
| [setLogicalDpiX(int value)](#setLogicalDpiX-int-) | mantıksal dpi x'i alır veya ayarlar. |
| [getLogicalDpiY()](#getLogicalDpiY--) | mantıksal dpi y'yi alır veya ayarlar. |
| [setLogicalDpiY(int value)](#setLogicalDpiY-int-) | mantıksal dpi y'yi alır veya ayarlar. |
| [getVersion()](#getVersion--) | sürümü alır veya ayarlar. |
| [setVersion(EmfPlusGraphicsVersion value)](#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-) | sürümü alır veya ayarlar. |
| [isValid()](#isValid--) | Bu örneğin geçerli olup olmadığını gösteren bir değeri alır. |
### EmfPlusHeader(EmfPlusRecord source) {#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusHeader(EmfPlusRecord source)
```


`EmfPlusHeader` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getDualMode() {#getDualMode--}
```
public boolean getDualMode()
```


Bu değeri alır veya ayarlar; [dual mode] olup olmadığını gösterir. Ayarlıysa, bu bayrak metafilenin "dual-mode" olduğunu gösterir; bu, iki kayıt kümesi içerdiği ve her birinin grafik içeriğini tamamen belirttiği anlamına gelir. Temizlenmişse, grafik içeriği EMF+ kayıtları ve muhtemelen bir EmfPlusGetDC kaydıyla önceden gelen EMF kayıtları tarafından belirtilir. Bu bayrak ayarlıysa, yalnızca EMF kayıtları GRAFİK içeriğini tanımlamak için YETERLİ olmalıdır. "dual-mode" bayrağının ayarlı olup olmamasına bakılmaksızın, bazı EMF kayıtları her zaman bulunur; bunlar EMF kontrol kayıtları ve EMF+ kayıtlarını içeren EMF kayıtlarıdır. EMF kontrol kayıtları, [MS-EMF] bölüm 2.3.4'te belirtilmiştir.

Değer: [dual mode] ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setDualMode(boolean value) {#setDualMode-boolean-}
```
public void setDualMode(boolean value)
```


Bu değeri alır veya ayarlar; [dual mode] olup olmadığını gösterir. Ayarlıysa, bu bayrak metafilenin "dual-mode" olduğunu gösterir; bu, iki kayıt kümesi içerdiği ve her birinin grafik içeriğini tamamen belirttiği anlamına gelir. Temizlenmişse, grafik içeriği EMF+ kayıtları ve muhtemelen bir EmfPlusGetDC kaydıyla önceden gelen EMF kayıtları tarafından belirtilir. Bu bayrak ayarlıysa, yalnızca EMF kayıtları GRAFİK içeriğini tanımlamak için YETERLİ olmalıdır. "dual-mode" bayrağının ayarlı olup olmamasına bakılmaksızın, bazı EMF kayıtları her zaman bulunur; bunlar EMF kontrol kayıtları ve EMF+ kayıtlarını içeren EMF kayıtlarıdır. EMF kontrol kayıtları, [MS-EMF] bölüm 2.3.4'te belirtilmiştir.

Değer: [dual mode] ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getVideoDisplay() {#getVideoDisplay--}
```
public boolean getVideoDisplay()
```


Video görüntüleme olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, bu bayrak metafilenin video görüntüleme için bir referans aygıt bağlamı ile kaydedildiğini gösterir. Temizlenmişse, metafile bir yazıcı için referans aygıt bağlamı ile kaydedilmiştir.

Değer: [video display] ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setVideoDisplay(boolean value) {#setVideoDisplay-boolean-}
```
public void setVideoDisplay(boolean value)
```


Video görüntüleme olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, bu bayrak metafilenin video görüntüleme için bir referans aygıt bağlamı ile kaydedildiğini gösterir. Temizlenmişse, metafile bir yazıcı için referans aygıt bağlamı ile kaydedilmiştir.

Değer: [video display] ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getEmfPlusFlags() {#getEmfPlusFlags--}
```
public int getEmfPlusFlags()
```


EMF plus bayraklarını alır veya ayarlar. Bu metafilenin nasıl kaydedildiği hakkında bilgi içeren 32 bit işaretsiz bir tam sayıdır. Alanın 31. biti ayarlıysa, bu bayrak metafilenin video görüntüleme için bir referans aygıt bağlamı ile kaydedildiğini gösterir. Temizlenmişse, metafile bir yazıcı için referans aygıt bağlamı ile kaydedilmiştir.

Değer: EMF plus bayrakları.

**Returns:**
int
### setEmfPlusFlags(int value) {#setEmfPlusFlags-int-}
```
public void setEmfPlusFlags(int value)
```


EMF plus bayraklarını alır veya ayarlar. Bu metafilenin nasıl kaydedildiği hakkında bilgi içeren 32 bit işaretsiz bir tam sayıdır. Alanın 31. biti ayarlıysa, bu bayrak metafilenin video görüntüleme için bir referans aygıt bağlamı ile kaydedildiğini gösterir. Temizlenmişse, metafile bir yazıcı için referans aygıt bağlamı ile kaydedilmiştir.

Değer: EMF plus bayrakları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLogicalDpiX() {#getLogicalDpiX--}
```
public int getLogicalDpiX()
```


Mantıksal dpi x'i alır veya ayarlar. Metafilenin kaydedildiği yatay çözünürlüğü inç başına piksel biriminde belirten 32 bit işaretsiz bir tam sayıdır.

Değer: Mantıksal dpi x.

**Returns:**
int
### setLogicalDpiX(int value) {#setLogicalDpiX-int-}
```
public void setLogicalDpiX(int value)
```


Mantıksal dpi x'i alır veya ayarlar. Metafilenin kaydedildiği yatay çözünürlüğü inç başına piksel biriminde belirten 32 bit işaretsiz bir tam sayıdır.

Değer: Mantıksal dpi x.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLogicalDpiY() {#getLogicalDpiY--}
```
public int getLogicalDpiY()
```


Mantıksal dpi y'yi alır veya ayarlar. Metafilenin kaydedildiği dikey çözünürlüğü inç başına satır biriminde belirten 32 bit işaretsiz bir tam sayıdır.

Değer: Mantıksal dpi y.

**Returns:**
int
### setLogicalDpiY(int value) {#setLogicalDpiY-int-}
```
public void setLogicalDpiY(int value)
```


Mantıksal dpi y'yi alır veya ayarlar. Metafilenin kaydedildiği dikey çözünürlüğü inç başına satır biriminde belirten 32 bit işaretsiz bir tam sayıdır.

Değer: Mantıksal dpi y.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getVersion() {#getVersion--}
```
public EmfPlusGraphicsVersion getVersion()
```


Sürümü alır veya ayarlar. Bu metafili oluşturmak için kullanılan işletim sistemi grafik sürümünü belirten bir EmfPlusGraphicsVersion nesnesi (bölüm 2.2.2.19).

Değer: Sürüm.

**Returns:**
[EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion)
### setVersion(EmfPlusGraphicsVersion value) {#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-}
```
public void setVersion(EmfPlusGraphicsVersion value)
```


Sürümü alır veya ayarlar. Bu metafili oluşturmak için kullanılan işletim sistemi grafik sürümünü belirten bir EmfPlusGraphicsVersion nesnesi (bölüm 2.2.2.19).

Değer: Sürüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion) |  |

### isValid() {#isValid--}
```
public boolean isValid()
```


Bu örneğin geçerli olup olmadığını gösteren bir değeri alır.

Değer: Bu örnek geçerliyse `true`; aksi takdirde `false`.

**Returns:**
boolean

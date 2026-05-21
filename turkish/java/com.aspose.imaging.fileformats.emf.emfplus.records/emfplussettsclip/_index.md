---
title: "EmfPlusSetTsClip"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusSetTSClip kaydı, bir terminal sunucu için grafik cihaz bağlamındaki kırpma alanlarını belirtir."
type: docs
weight: 66
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsClip extends EmfPlusTerminalServerRecordType
```

EmfPlusSetTSClip kaydı, bir terminal sunucu için grafik cihaz bağlamındaki kırpma alanlarını belirtir.

Bu kayıttaki veri için sıkıştırma şeması aşağıdaki algoritmayı kullanır. Her dikdörtgenin her noktası tek bir bayt ya da 2 bayt ile kodlanır. Nokta tek bir bayt ile kodlanıyorsa, baytın yüksek biti (0x80) AYARLANMALI ve değer, alt 7 bit tarafından temsil edilen işaretli bir sayı olur. Yüksek bit ayarlı değilse, değer 2 bayt ile kodlanır; yüksek bayt ilk baytın alt 7 biti içinde kodlanır ve düşük bayt değeri ikinci baytta kodlanır. Her nokta, mevcut dikdörtgendeki nokta ile önceki dikdörtgendeki nokta arasındaki fark olarak kodlanır. Dikdörtgenin alt noktası, mevcut dikdörtgendeki alt koordinat ile üst koordinat arasındaki fark olarak kodlanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusSetTsClip(EmfPlusRecord source)](#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusSetTsClip` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCompressed()](#getCompressed--) | Bu `EmfPlusSetTsClip` nesnesinin sıkıştırılmış olup olmadığını gösteren bir değeri alır. |
| [getNumRects()](#getNumRects--) | Rect sayısını alır. |
| [getRects()](#getRects--) | Kırpma alanlarını tanımlayan NumRects dikdörtgenlerinden oluşan bir dizi alır veya ayarlar. |
| [setRects(Rectangle[] value)](#setRects-com.aspose.imaging.Rectangle---) | Kırpma alanlarını tanımlayan NumRects dikdörtgenlerinden oluşan bir dizi alır veya ayarlar. |
### EmfPlusSetTsClip(EmfPlusRecord source) {#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsClip(EmfPlusRecord source)
```


`EmfPlusSetTsClip` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


`EmfPlusSetTsClip` öğesinin sıkıştırılmış olup olmadığını gösteren bir değer alır. Bu bit, rects alanındaki dikdörtgen verisinin formatını belirtir. Ayarlıysa, her dikdörtgen 4 bayt içinde tanımlanır. Temizse, her dikdörtgen 8 bayt içinde tanımlanır.

Değer: sıkıştırılmışsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### getNumRects() {#getNumRects--}
```
public short getNumRects()
```


Rect sayısını alır. Bu alan, rect alanında tanımlanan dikdörtgen sayısını belirtir.

Değer: Rect sayısı.

**Returns:**
short
### getRects() {#getRects--}
```
public Rectangle[] getRects()
```


Kırpma alanlarını tanımlayan NumRects dikdörtgenlerinden oluşan bir dizi alır veya ayarlar. Bu verinin formatı, Flags alanındaki C biti tarafından belirlenir.

Değer: Rects.

**Returns:**
com.aspose.imaging.Rectangle[]
### setRects(Rectangle[] value) {#setRects-com.aspose.imaging.Rectangle---}
```
public void setRects(Rectangle[] value)
```


Kırpma alanlarını tanımlayan NumRects dikdörtgenlerinden oluşan bir dizi alır veya ayarlar. Bu verinin formatı, Flags alanındaki C biti tarafından belirlenir.

Değer: Rects.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |


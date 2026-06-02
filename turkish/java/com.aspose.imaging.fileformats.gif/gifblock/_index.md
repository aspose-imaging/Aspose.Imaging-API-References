---
title: "GifBlock"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Varsayılan gif blok uygulaması."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.gif/gifblock/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
```
public abstract class GifBlock implements IGifBlock
```

Varsayılan gif blok uygulaması.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GifBlock()](#GifBlock--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [EXTENSION_INTRODUCER](#EXTENSION-INTRODUCER) | Uzantı tanıtıcı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isChanged()](#isChanged--) | Bloğun değişip değişmediğini ve kaydedilmesi gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| [setChanged(boolean value)](#setChanged-boolean-) | Bloğun değişip değişmediğini ve kaydedilmesi gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Bloğu belirtilen akışa kaydeder. |
### GifBlock() {#GifBlock--}
```
public GifBlock()
```


### EXTENSION_INTRODUCER {#EXTENSION-INTRODUCER}
```
public static final byte EXTENSION_INTRODUCER
```


Uzantı tanıtıcı.

### isChanged() {#isChanged--}
```
public boolean isChanged()
```


Bloğun değişip değişmediğini ve kaydedilmesi gerekip gerekmediğini gösteren bir değeri alır veya ayarlar.

Değer: blok değiştiyse `true`; aksi takdirde `false`.

**Returns:**
boolean
### setChanged(boolean value) {#setChanged-boolean-}
```
public void setChanged(boolean value)
```


Bloğun değişip değişmediğini ve kaydedilmesi gerekip gerekmediğini gösteren bir değeri alır veya ayarlar.

Değer: blok değiştiyse `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Bloğu belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Verilerin kaydedileceği akış. |


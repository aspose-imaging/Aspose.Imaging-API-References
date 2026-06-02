---
title: "EmfModifyWorldTransformMode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "ModifyWorldTransformMode sayımı, oynatma cihaz bağlamında şu anda tanımlı olan dünya-uzayından sayfa-uzayına dönüşümü değiştirmek için belirtilen dönüşüm verilerini kullanma modlarını tanımlar."
type: docs
weight: 33
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfModifyWorldTransformMode extends System.Enum
```

ModifyWorldTransformMode sayımı, oynatma cihaz bağlamında şu anda tanımlı olan dünya-uzayından sayfa-uzayına dönüşümü değiştirmek için belirtilen dönüşüm verilerini kullanma modlarını tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [MWT_IDENTITY](#MWT-IDENTITY) | Kimlik matrisini kullanarak geçerli dönüşümü sıfırla. |
| [MWT_LEFTMULTIPLY](#MWT-LEFTMULTIPLY) | Geçerli dönüşümü çarp. |
| [MWT_RIGHTMULTIPLY](#MWT-RIGHTMULTIPLY) | Geçerli dönüşümü çarp. |
| [MWT_SET](#MWT-SET) | EMR\_SETWORLDTRANSFORM kaydının işlevini gerçekleştir (bölüm 2.3.12.2). |
### MWT_IDENTITY {#MWT-IDENTITY}
```
public static final int MWT_IDENTITY
```


Geçerli dönüşümü birim matris kullanarak sıfırla. Bu modda, belirtilen dönüşüm verisi yok sayılır.

### MWT_LEFTMULTIPLY {#MWT-LEFTMULTIPLY}
```
public static final int MWT_LEFTMULTIPLY
```


Geçerli dönüşümü çarp. Bu modda, belirtilen dönüşüm verisi sol çarpan, ve oynatma aygıt bağlamında şu anda tanımlı dönüşüm sağ çarpandır.

### MWT_RIGHTMULTIPLY {#MWT-RIGHTMULTIPLY}
```
public static final int MWT_RIGHTMULTIPLY
```


Geçerli dönüşümü çarp. Bu modda, belirtilen dönüşüm verisi sağ çarpan, ve oynatma aygıt bağlamında şu anda tanımlı dönüşüm sol çarpandır.

### MWT_SET {#MWT-SET}
```
public static final int MWT_SET
```


EMR\_SETWORLDTRANSFORM kaydının işlevini gerçekleştir (bölüm 2.3.12.2).


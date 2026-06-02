---
title: "WmfTextAlignmentModeFlags"
second_title: "Aspose.Imaging for Java API Referansı"
description: "TextAlignmentMode Bayrakları, bir referans noktası ile metin hizalaması için sınırlayıcı dikdörtgen arasındaki ilişkiyi belirtir."
type: docs
weight: 36
url: /tr/java/com.aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfTextAlignmentModeFlags extends System.Enum
```

TextAlignmentMode Bayrakları, bir referans noktası ile sınırlayıcı dikdörtgen arasındaki ilişkiyi, metin hizalaması için belirtir. Bu bayraklar birden fazla seçeneği belirtmek için birleştirilebilir, ancak yalnızca bir bayrak, oynatma aygıt bağlamındaki çizim konumunu değiştirebilir. Yazı tipi yatay varsayılan bir temel çizgiye sahip olduğunda yatay metin hizalaması gerçekleştirilir.

--------------------

TextAlignmentMode bayrakları, metin hizalamasının üç farklı bileşenini belirtir: - Referans noktasının yatay konumu TA\_RIGHT ve TA\_CENTER ile belirlenir; bu bitler temizse hizalama TA\_LEFT olmalıdır. - Referans noktasının dikey konumu TA\_BOTTOM ve TA\_BASELINE ile belirlenir; bu bitler temizse hizalama TA\_TOP olmalıdır. - Metin çıktısı sonrası oynatma aygıt bağlamındaki çıktı konumunun güncellenip güncellenmeyeceği TA\_UPDATECP ile belirlenir; bu bit temizse konum GÜNCELLENMEMELİDİR. Bu, enum içinde üç farklı sıfır değerinin tanımlanma nedenidir; bunlar metin hizalamasının üç bileşeninin varsayılan durumlarını temsil eder.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | Oynatma aygıt bağlamındaki çizim konumu, her metin çıktısı çağrısından sonra GÜNCELLENMEMELİDİR. |
| [Left](#Left) | Referans noktası, sınırlayıcı dikdörtgenin sol kenarında OLMAK ZORUNDADIR. |
| [Top](#Top) | Referans noktası, sınırlayıcı dikdörtgenin üst kenarında OLMAK ZORUNDADIR. |
| [Updatecp](#Updatecp) | Oynatma aygıt bağlamındaki çizim konumu, her metin çıktısı çağrısından sonra GÜNCELLENMELİDİR. |
| [Right](#Right) | Referans noktası, sınırlayıcı dikdörtgenin sağ kenarında OLMAK ZORUNDADIR. |
| [Center](#Center) | Referans noktası, sınırlayıcı dikdörtgenin ortasıyla yatay olarak hizalanmalıdır. |
| [Bottom](#Bottom) | Referans noktası, sınırlayıcı dikdörtgenin alt kenarında OLMAK ZORUNDADIR. |
| [Baseline](#Baseline) | Referans noktası, metnin taban çizgisinde OLMAK ZORUNDADIR. |
| [Rtlreading](#Rtlreading) | Metin, varsayılan soldan sağa sıralama yerine sağdan sola okuma düzeninde yerleştirilmelidir. |
| [Horizontal](#Horizontal) | Represents Horizontal text align sets (Left | Right | Center) |
| [Vertical](#Vertical) | Represents Vertical text align sets (Top | Bottom | Baseline) |
### Noupdatecp {#Noupdatecp}
```
public static final int Noupdatecp
```


Oynatma aygıt bağlamındaki çizim konumu, her metin çıktısı çağrısından sonra GÜNCELLENMEMELİDİR. Referans noktasının metin çıktısı işlevine geçirilmesi GEREKİR.

### Left {#Left}
```
public static final int Left
```


Referans noktası, sınırlayıcı dikdörtgenin sol kenarında OLMAK ZORUNDADIR.

### Top {#Top}
```
public static final int Top
```


Referans noktası, sınırlayıcı dikdörtgenin üst kenarında OLMAK ZORUNDADIR.

### Updatecp {#Updatecp}
```
public static final int Updatecp
```


Oynatma aygıt bağlamındaki çizim konumu, her metin çıktısı çağrısından sonra GÜNCELLENMELİDİR. Bu, referans noktası olarak kullanılmalıdır.

### Right {#Right}
```
public static final int Right
```


Referans noktası, sınırlayıcı dikdörtgenin sağ kenarında OLMAK ZORUNDADIR.

### Center {#Center}
```
public static final int Center
```


Referans noktası, sınırlayıcı dikdörtgenin ortasıyla yatay olarak hizalanmalıdır.

### Bottom {#Bottom}
```
public static final int Bottom
```


Referans noktası, sınırlayıcı dikdörtgenin alt kenarında OLMAK ZORUNDADIR.

### Baseline {#Baseline}
```
public static final int Baseline
```


Referans noktası, metnin taban çizgisinde OLMAK ZORUNDADIR.

### Rtlreading {#Rtlreading}
```
public static final int Rtlreading
```


Metin, varsayılan soldan sağa sıralama yerine sağdan sola okuma düzeninde yerleştirilmelidir. Bu, yalnızca oynatma aygıt bağlamında tanımlı yazı tipi İbranice veya Arapça olduğunda UYGULANMALIDIR.

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Yatay metin hizalama kümelerini temsil eder (Left | Right | Center)

### Vertical {#Vertical}
```
public static final int Vertical
```


Dikey metin hizalama kümelerini temsil eder (Top | Bottom | Baseline)


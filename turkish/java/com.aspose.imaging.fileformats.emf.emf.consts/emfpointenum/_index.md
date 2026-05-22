---
title: "EmfPointEnum"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Point sayımı, bir noktanın çizim çağrısında nasıl kullanılacağını belirtmek için kullanılır."
type: docs
weight: 35
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPointEnum extends System.Enum
```

Point sayımı, bir noktanın çizim çağrısında nasıl kullanılacağını belirtmek için kullanılır.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [PT_CLOSEFIGURE](#PT-CLOSEFIGURE) | Bir PT\_LINETO veya PT\_BEZIERTO türü, ilgili noktanın bir şeklin son noktası olduğunu ve şeklin kapalı olduğunu göstermek için bu değerle bit düzeyinde OR operatörü kullanılarak birleştirilebilir. |
| [PT_LINETO](#PT-LINETO) | Bir çizginin mevcut konumdan bu noktaya çizileceğini ve ardından bu noktanın yeni mevcut konum olacağını belirtir. |
| [PT_BEZIERTO](#PT-BEZIERTO) | Bu noktanın bir Bezier eğrisi için kontrol noktası veya bitiş noktası olduğunu belirtir. |
| [PT_MOVETO](#PT-MOVETO) | Bu noktanın ayrı bir şekil başlattığını belirtir. |
### PT_CLOSEFIGURE {#PT-CLOSEFIGURE}
```
public static final byte PT_CLOSEFIGURE
```


Bir PT\_LINETO veya PT\_BEZIERTO türü, ilgili noktanın bir şeklin son noktası olduğunu ve şeklin kapalı olduğunu göstermek için bu değerle bit düzeyinde OR operatörü kullanılarak birleştirilebilir.

### PT_LINETO {#PT-LINETO}
```
public static final byte PT_LINETO
```


Bir çizginin mevcut konumdan bu noktaya çizileceğini ve ardından bu noktanın yeni mevcut konum olacağını belirtir.

### PT_BEZIERTO {#PT-BEZIERTO}
```
public static final byte PT_BEZIERTO
```


Bu noktanın bir Bezier eğrisi için kontrol noktası veya bitiş noktası olduğunu belirtir.

### PT_MOVETO {#PT-MOVETO}
```
public static final byte PT_MOVETO
```


Bu noktanın ayrı bir şekil başlattığını belirtir. Bu nokta yeni mevcut konum olur.


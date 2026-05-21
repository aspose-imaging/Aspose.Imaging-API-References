---
title: "EmfMapMode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "MapMode sayımı, sayfa uzayı birimlerini cihaz uzayı birimlerine dönüştürmek ve çizim eksenlerinin yönünü tanımlamak için ölçü birimini belirlemek amacıyla kullanılır."
type: docs
weight: 30
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfMapMode extends System.Enum
```

MapMode sayımı, sayfa uzayı birimlerini cihaz uzayı birimlerine dönüştürmek ve çizim eksenlerinin yönünü tanımlamak için ölçü birimini belirlemek amacıyla kullanılır.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [MM_TEXT](#MM-TEXT) | Her mantıksal birim bir cihaz pikseline eşlenir. |
| [MM_LOMETRIC](#MM-LOMETRIC) | Her mantıksal birim 0,1 milimetreye eşlenir. |
| [MM_HIMETRIC](#MM-HIMETRIC) | Her mantıksal birim 0,01 milimetreye eşlenir. |
| [MM_LOENGLISH](#MM-LOENGLISH) | Her mantıksal birim 0,01 inçe eşlenir. |
| [MM_HIENGLISH](#MM-HIENGLISH) | Her mantıksal birim 0,001 inçe eşlenir. |
| [MM_TWIPS](#MM-TWIPS) | Her mantıksal birim bir yazıcı noktasının yirminci birine (1/1440 inç, aynı zamanda "twip" olarak da adlandırılır) eşlenir. |
| [MM_ISOTROPIC](#MM-ISOTROPIC) | Mantıksal birimler eşit ölçekli eksenlerle keyfi birimlere eşlenir; yani x ekseni boyunca bir birim y ekseni boyunca bir birime eşittir. |
| [MM_ANISOTROPIC](#MM-ANISOTROPIC) | Mantıksal birimler keyfi birimlere, keyfi ölçekli eksenlerle eşlenir. |
### MM_TEXT {#MM-TEXT}
```
public static final int MM_TEXT
```


Her mantıksal birim bir cihaz pikseline eşlenir. Pozitif x sağa, pozitif y aşağıya yöneliktir.

### MM_LOMETRIC {#MM-LOMETRIC}
```
public static final int MM_LOMETRIC
```


Her mantıksal birim 0,1 milimetreye eşlenir. Pozitif x sağa, pozitif y yukarıya yöneliktir.

### MM_HIMETRIC {#MM-HIMETRIC}
```
public static final int MM_HIMETRIC
```


Her mantıksal birim 0,01 milimetreye eşlenir. Pozitif x sağa, pozitif y yukarıya yöneliktir.

### MM_LOENGLISH {#MM-LOENGLISH}
```
public static final int MM_LOENGLISH
```


Her mantıksal birim 0,01 inçe eşlenir. Pozitif x sağa, pozitif y yukarıya yöneliktir

### MM_HIENGLISH {#MM-HIENGLISH}
```
public static final int MM_HIENGLISH
```


Her mantıksal birim 0,001 inçe eşlenir. Pozitif x sağa, pozitif y yukarıya yöneliktir.

### MM_TWIPS {#MM-TWIPS}
```
public static final int MM_TWIPS
```


Her mantıksal birim bir yazıcı noktasının yirminci birine (1/1440 inç, aynı zamanda "twip" olarak da adlandırılır) eşlenir. Pozitif x sağa, pozitif y yukarıya yöneliktir.

### MM_ISOTROPIC {#MM-ISOTROPIC}
```
public static final int MM_ISOTROPIC
```


Mantıksal birimler eşit ölçekli eksenlerle keyfi birimlere eşlenir; yani x ekseni boyunca bir birim y ekseni boyunca bir birime eşittir. EMR\_SETWINDOWEXTEX ve EMR\_SETVIEWPORTEXTEX kayıtları, birimleri ve eksenlerin yönelimini belirtmek için SHOULD kullanılmalıdır. Gerekli olduğunda, x ve y birimlerinin aynı boyutta kalmasını sağlamak için Adjustments MUST yapılmalıdır. Örneğin, pencere ölçüsü ayarlandığında, viewport MUST birimleri izotropik tutacak şekilde ayarlanmalıdır.

### MM_ANISOTROPIC {#MM-ANISOTROPIC}
```
public static final int MM_ANISOTROPIC
```


Mantıksal birimler keyfi birimlere, keyfi ölçekli eksenlerle eşlenir. EMR\_SETWINDOWEXTEX ve EMR\_SETVIEWPORTEXTEX kayıtları, birimleri, yönelimi ve ölçeklemeyi belirtmek için SHOULD kullanılmalıdır.


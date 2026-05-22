---
title: "EmfStretchMode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "StretchMode sayımı, gerilen veya sıkıştırılan bitmap'lere renk verisinin nasıl ekleneceğini veya kaldırılacağını belirtmek için kullanılır."
type: docs
weight: 43
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStretchMode extends System.Enum
```

StretchMode sayımı, gerilen veya sıkıştırılan bitmap'lere renk verisinin nasıl ekleneceğini veya kaldırılacağını belirtmek için kullanılır.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [STRETCH_ANDSCANS](#STRETCH-ANDSCANS) | Elimine edilen ve mevcut piksellerin renk değerlerini kullanarak bir Boolean AND işlemi gerçekleştirir. |
| [STRETCH_ORSCANS](#STRETCH-ORSCANS) | Elimine edilen ve mevcut piksellerin renk değerlerini kullanarak bir Boolean OR işlemi gerçekleştirir. |
| [STRETCH_DELETESCANS](#STRETCH-DELETESCANS) | Piksel'leri siler. |
| [STRETCH_HALFTONE](#STRETCH-HALFTONE) | Kaynak dikdörtgenden pikselleri hedef dikdörtgendeki piksel bloklarına eşler. |
### STRETCH_ANDSCANS {#STRETCH-ANDSCANS}
```
public static final int STRETCH_ANDSCANS
```


Elimin edilen ve mevcut piksellerin renk değerlerini kullanarak bir Boolean VE işlemi gerçekleştirir. Bitmap tek renkli bir bitmap ise, bu mod beyaz piksellerin pahasına siyah pikselleri korur.

### STRETCH_ORSCANS {#STRETCH-ORSCANS}
```
public static final int STRETCH_ORSCANS
```


Elimin edilen ve mevcut piksellerin renk değerlerini kullanarak bir Boolean VEYA işlemi gerçekleştirir. Bitmap tek renkli bir bitmap ise, bu mod siyah piksellerin pahasına beyaz pikselleri korur.

### STRETCH_DELETESCANS {#STRETCH-DELETESCANS}
```
public static final int STRETCH_DELETESCANS
```


Piksel'leri siler. Bu mod, bilgilerini korumaya çalışmadan tüm elimin edilen piksel satırlarını siler.

### STRETCH_HALFTONE {#STRETCH-HALFTONE}
```
public static final int STRETCH_HALFTONE
```


Kaynak dikdörtgenden pikselleri hedef dikdörtgendeki piksel bloklarına eşler. Hedef piksel bloğunun ortalama rengi, kaynak piksellerin rengini yaklaşık olarak yansıtır.


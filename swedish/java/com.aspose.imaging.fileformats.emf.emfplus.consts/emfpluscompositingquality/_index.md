---
title: "EmfPlusCompositingQuality"
second_title: "Aspose.Imaging för Java API-referens"
description: "CompositingQuality‑enumerationen definierar kvalitetsnivåer för att skapa sammansatta bilder"
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingQuality extends System.Enum
```

CompositingQuality‑enumerationen definierar kvalitetsnivåer för att skapa sammansatta bilder
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CompositingQualityDefault](#CompositingQualityDefault) | Ingen gamma correction utförs. |
| [CompositingQualityHighSpeed](#CompositingQualityHighSpeed) | Ingen gamma correction utförs. |
| [CompositingQualityHighQuality](#CompositingQualityHighQuality) | Gamma correction utförs. |
| [CompositingQualityGammaCorrected](#CompositingQualityGammaCorrected) | Aktivera gamma correction för högre kvalitet på sammanslagning med lägre hastighet. |
| [CompositingQualityAssumeLinear](#CompositingQualityAssumeLinear) | Ingen gamma correction utförs; dock ger användning av linjära värden bättre kvalitet än standardvärdet med en något lägre hastighet. |
### CompositingQualityDefault {#CompositingQualityDefault}
```
public static final byte CompositingQualityDefault
```


Ingen gamma correction utförs. Gamma correction styr bildens totala ljusstyrka och kontrast. Utan gamma correction kan sammanslagna bilder framstå som för ljusa eller för mörka.

### CompositingQualityHighSpeed {#CompositingQualityHighSpeed}
```
public static final byte CompositingQualityHighSpeed
```


Ingen gamma correction utförs. Sammanslagningshastigheten prioriteras på bekostnad av kvalitet. När det gäller resultatet finns ingen skillnad mellan detta värde och CompositingQualityDefault.

### CompositingQualityHighQuality {#CompositingQualityHighQuality}
```
public static final byte CompositingQualityHighQuality
```


Gamma correction utförs. Sammanslagningskvaliteten prioriteras på bekostnad av hastighet.

### CompositingQualityGammaCorrected {#CompositingQualityGammaCorrected}
```
public static final byte CompositingQualityGammaCorrected
```


Aktivera gamma correction för högre kvalitet på sammanslagning med lägre hastighet. När det gäller resultatet finns ingen skillnad mellan detta värde och CompositingQualityHighQuality.

### CompositingQualityAssumeLinear {#CompositingQualityAssumeLinear}
```
public static final byte CompositingQualityAssumeLinear
```


Ingen gamma correction utförs; dock ger användning av linjära värden bättre kvalitet än standardvärdet med en något lägre hastighet.


---
title: "EmfPlusCompositingQuality"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Aufzählung CompositingQuality definiert Qualitätsstufen für die Erstellung zusammengesetzter Bilder."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingQuality extends System.Enum
```

Die Aufzählung CompositingQuality definiert Qualitätsstufen für die Erstellung zusammengesetzter Bilder.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CompositingQualityDefault](#CompositingQualityDefault) | Es wird keine Gamma-Korrektur durchgeführt. |
| [CompositingQualityHighSpeed](#CompositingQualityHighSpeed) | Es wird keine Gamma-Korrektur durchgeführt. |
| [CompositingQualityHighQuality](#CompositingQualityHighQuality) | Gamma-Korrektur wird durchgeführt. |
| [CompositingQualityGammaCorrected](#CompositingQualityGammaCorrected) | Aktivieren Sie die Gamma-Korrektur für eine qualitativ hochwertigere Kompositierung bei geringerer Geschwindigkeit. |
| [CompositingQualityAssumeLinear](#CompositingQualityAssumeLinear) | Es wird keine Gamma-Korrektur durchgeführt; die Verwendung linearer Werte führt jedoch zu einer besseren Qualität als die Standardeinstellung bei leicht geringerer Geschwindigkeit. |
### CompositingQualityDefault {#CompositingQualityDefault}
```
public static final byte CompositingQualityDefault
```


Es wird keine Gamma-Korrektur durchgeführt. Gamma-Korrektur steuert die Gesamthelligkeit und den Kontrast eines Bildes. Ohne Gamma-Korrektur können zusammengesetzte Bilder zu hell oder zu dunkel erscheinen.

### CompositingQualityHighSpeed {#CompositingQualityHighSpeed}
```
public static final byte CompositingQualityHighSpeed
```


Es wird keine Gamma-Korrektur durchgeführt. Die Kompositierungsgeschwindigkeit wird zugunsten der Qualität bevorzugt. Was das Ergebnis betrifft, gibt es keinen Unterschied zwischen diesem Wert und CompositingQualityDefault.

### CompositingQualityHighQuality {#CompositingQualityHighQuality}
```
public static final byte CompositingQualityHighQuality
```


Gamma-Korrektur wird durchgeführt. Die Kompositierungsqualität wird zugunsten der Geschwindigkeit bevorzugt.

### CompositingQualityGammaCorrected {#CompositingQualityGammaCorrected}
```
public static final byte CompositingQualityGammaCorrected
```


Aktivieren Sie die Gamma-Korrektur für eine qualitativ hochwertigere Kompositierung bei geringerer Geschwindigkeit. Was das Ergebnis betrifft, gibt es keinen Unterschied zwischen diesem Wert und CompositingQualityHighQuality.

### CompositingQualityAssumeLinear {#CompositingQualityAssumeLinear}
```
public static final byte CompositingQualityAssumeLinear
```


Es wird keine Gamma-Korrektur durchgeführt; die Verwendung linearer Werte führt jedoch zu einer besseren Qualität als die Standardeinstellung bei leicht geringerer Geschwindigkeit.


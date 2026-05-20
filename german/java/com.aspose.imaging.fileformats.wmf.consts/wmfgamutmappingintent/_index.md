---
title: "WmfGamutMappingIntent"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die GamutMappingIntent‑Aufzählung gibt die Beziehung zwischen logischen und physischen Farben an."
type: docs
weight: 20
url: /de/java/com.aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfGamutMappingIntent extends System.Enum
```

Die GamutMappingIntent‑Aufzählung gibt die Beziehung zwischen logischen und physischen Farben an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [LCS_GM_ABS_COLORIMETRIC](#LCS-GM-ABS-COLORIMETRIC) | Gibt an, dass der Weißpunkt BEWAHRT werden SOLLTE. |
| [LCS_GM_BUSINESS](#LCS-GM-BUSINESS) | Gibt an, dass die Sättigung **SHOULD** beibehalten werden soll. |
| [LCS_GM_GRAPHICS](#LCS-GM-GRAPHICS) | Gibt an, dass eine kolorimetrische Übereinstimmung **SHOULD** beibehalten werden soll. |
| [LCS_GM_IMAGES](#LCS-GM-IMAGES) | Gibt an, dass der Kontrast **SHOULD** beibehalten werden soll. |
### LCS_GM_ABS_COLORIMETRIC {#LCS-GM-ABS-COLORIMETRIC}
```
public static final int LCS_GM_ABS_COLORIMETRIC
```


Gibt an, dass der Weißpunkt **SHOULD** beibehalten werden soll. Wird typischerweise verwendet, wenn logische Farben **MUST** an ihre nächstgelegene physische Farbe im Ziel‑Farb gamut angepasst werden müssen. Intent: Match ICC name: Absolute Colorimetric

### LCS_GM_BUSINESS {#LCS-GM-BUSINESS}
```
public static final int LCS_GM_BUSINESS
```


Gibt an, dass die Sättigung **SHOULD** beibehalten werden soll. Wird typischerweise für Geschäftsgrafiken und andere Situationen verwendet, in denen Dithering nicht erforderlich ist. Intent: Graphic ICC name: Saturation

### LCS_GM_GRAPHICS {#LCS-GM-GRAPHICS}
```
public static final int LCS_GM_GRAPHICS
```


Gibt an, dass eine kolorimetrische Übereinstimmung **SHOULD** beibehalten werden soll. Wird typischerweise für Grafikdesigns und benannte Farben verwendet. Intent: Proof ICC name: Relative Colorimetric

### LCS_GM_IMAGES {#LCS-GM-IMAGES}
```
public static final int LCS_GM_IMAGES
```


Gibt an, dass der Kontrast **SHOULD** beibehalten werden soll. Wird typischerweise für Fotografien und natürliche Bilder verwendet. Intent: Picture ICC name: Perceptual


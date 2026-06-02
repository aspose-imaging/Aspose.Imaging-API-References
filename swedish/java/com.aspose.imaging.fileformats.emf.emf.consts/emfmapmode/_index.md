---
title: "EmfMapMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "MapMode-enumerationen används för att definiera måttenheten för att omvandla sidrymdsenheter till enhetsrymdsenheter samt för att definiera orienteringen av ritningsaxlarna."
type: docs
weight: 30
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfMapMode extends System.Enum
```

MapMode-enumerationen används för att definiera måttenheten för att omvandla sidrymdsenheter till enhetsrymdsenheter samt för att definiera orienteringen av ritningsaxlarna.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [MM_TEXT](#MM-TEXT) | Varje logisk enhet mappas till en enhetspixel. |
| [MM_LOMETRIC](#MM-LOMETRIC) | Varje logisk enhet mappas till 0,1 millimeter. |
| [MM_HIMETRIC](#MM-HIMETRIC) | Varje logisk enhet mappas till 0,01 millimeter. |
| [MM_LOENGLISH](#MM-LOENGLISH) | Varje logisk enhet mappas till 0,01 tum. |
| [MM_HIENGLISH](#MM-HIENGLISH) | Varje logisk enhet mappas till 0,001 tum. |
| [MM_TWIPS](#MM-TWIPS) | Varje logisk enhet mappas till en tjugondel av ett skrivarpunkt (1/1440 tum, även kallad \"twip\"). |
| [MM_ISOTROPIC](#MM-ISOTROPIC) | Logiska enheter mappas till godtyckliga enheter med lika skalade axlar; det vill säga, en enhet längs x-axeln är lika med en enhet längs y-axeln. |
| [MM_ANISOTROPIC](#MM-ANISOTROPIC) | Logiska enheter mappas till godtyckliga enheter med godtyckligt skalade axlar. |
### MM_TEXT {#MM-TEXT}
```
public static final int MM_TEXT
```


Varje logisk enhet mappas till en enhetspixel. Positiv x är åt höger; positiv y är nedåt.

### MM_LOMETRIC {#MM-LOMETRIC}
```
public static final int MM_LOMETRIC
```


Varje logisk enhet mappas till 0,1 millimeter. Positiv x är åt höger; positiv y är uppåt.

### MM_HIMETRIC {#MM-HIMETRIC}
```
public static final int MM_HIMETRIC
```


Varje logisk enhet mappas till 0,01 millimeter. Positiv x är åt höger; positiv y är uppåt.

### MM_LOENGLISH {#MM-LOENGLISH}
```
public static final int MM_LOENGLISH
```


Varje logisk enhet mappas till 0,01 tum. Positiv x är åt höger; positiv y är uppåt

### MM_HIENGLISH {#MM-HIENGLISH}
```
public static final int MM_HIENGLISH
```


Varje logisk enhet mappas till 0,001 tum. Positiv x är åt höger; positiv y är uppåt.

### MM_TWIPS {#MM-TWIPS}
```
public static final int MM_TWIPS
```


Varje logisk enhet mappas till en tjugondel av ett skrivarpunkt (1/1440 tum, även kallad \"twip\"). Positiv x är åt höger; positiv y är uppåt.

### MM_ISOTROPIC {#MM-ISOTROPIC}
```
public static final int MM_ISOTROPIC
```


Logiska enheter mappas till godtyckliga enheter med lika skalade axlar; det vill säga, en enhet längs x-axeln är lika med en enhet längs y-axeln. EMR\_SETWINDOWEXTEX och EMR\_SETVIEWPORTEXTEX poster SKA användas för att specificera enheterna och axlarnas orientering. Justeringar MÅSTE göras vid behov för att säkerställa att x- och y-enheterna behåller samma storlek. Till exempel, när fönsterutbredningen sätts, måste viewporten justeras för att hålla enheterna isotropa.

### MM_ANISOTROPIC {#MM-ANISOTROPIC}
```
public static final int MM_ANISOTROPIC
```


Logiska enheter mappas till godtyckliga enheter med godtyckligt skalade axlar. EMR\_SETWINDOWEXTEX och EMR\_SETVIEWPORTEXTEX poster SKA användas för att specificera enheterna, orienteringen och skalningen.


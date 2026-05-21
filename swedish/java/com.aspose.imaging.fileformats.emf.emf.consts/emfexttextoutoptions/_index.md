---
title: "EmfExtTextOutOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "ExtTextOutOptions‑enumerationen specificerar parametrar som styr olika aspekter av textutmatning via EMR_SMALLTEXTOUT‑sektion 2.3.5.37‑poster och i EmrText‑objekt."
type: docs
weight: 19
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfExtTextOutOptions extends System.Enum
```

ExtTextOutOptions-enumerationen specificerar parametrar som styr olika aspekter av textutdata via EMR\_SMALLTEXTOUT (avsnitt 2.3.5.37) poster och i EmrText-objekt.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ETO_OPAQUE](#ETO-OPAQUE) | Denna bit indikerar att den aktuella bakgrundsfärgen SKALL användas för att fylla rektangeln. |
| [ETO_CLIPPED](#ETO-CLIPPED) | Denna bit indikerar att texten SKALL klippas till rektangeln. |
| [ETO_GLYPH_INDEX](#ETO-GLYPH-INDEX) | Denna bit indikerar att koderna för tecken i en utmatningssträng faktiskt är index för teckenglyfer i ett TrueType‑teckensnitt. |
| [ETO_RTLREADING](#ETO-RTLREADING) | Denna bit indikerar att texten MÅSTE läggas ut i högra‑till‑vänstra läsordning, istället för standardvänstra‑till‑högra ordning. |
| [ETO_NO_RECT](#ETO-NO-RECT) | Denna bit indikerar att posten inte specificerar en avgränsande rektangel för textutmatningen. |
| [ETO_SMALL_CHARS](#ETO-SMALL-CHARS) | Denna bit indikerar att koderna för tecken i en utmatningssträng är 8‑bitars, härledda från de låga byten i 16‑bitars Unicode UTF16‑LE‑teckenkoder, där den högre byten antas vara 0. |
| [ETO_NUMERICSLOCAL](#ETO-NUMERICSLOCAL) | Denna bit indikerar att för att visa siffror bör lokalanpassade tecken användas. |
| [ETO_NUMERICSLATIN](#ETO-NUMERICSLATIN) | Denna bit indikerar att för att visa siffror bör europeiska siffror användas. |
| [ETO_IGNORELANGUAGE](#ETO-IGNORELANGUAGE) | Denna bit indikerar att ingen speciell operativsystembehandling för glyfplacering ska utföras på högra‑till‑vänstra strängar; det vill säga, all glyfpositionering SKALL hanteras av rit‑ och tillståndsposter i metafilen. |
| [ETO_PDY](#ETO-PDY) | Denna bit indikerar att både horisontella och vertikala teckenförskjutningsvärden SKALL tillhandahållas. |
| [ETO_REVERSE_INDEX_MAP](#ETO-REVERSE-INDEX-MAP) | Denna bit är reserverad och SKALL INTE användas. |
### ETO_OPAQUE {#ETO-OPAQUE}
```
public static final int ETO_OPAQUE
```


Denna bit indikerar att den aktuella bakgrundsfärgen SKALL användas för att fylla rektangeln.

### ETO_CLIPPED {#ETO-CLIPPED}
```
public static final int ETO_CLIPPED
```


Denna bit indikerar att texten SKALL klippas till rektangeln.

### ETO_GLYPH_INDEX {#ETO-GLYPH-INDEX}
```
public static final int ETO_GLYPH_INDEX
```


Denna bit indikerar att koderna för tecken i en utmatningssträng faktiskt är index för teckenglyfer i ett TrueType‑teckensnitt. Glyfindex är typsnittsspecifika, så för att visa rätt tecken vid uppspelning måste det använda teckensnittet vara identiskt med det teckensnitt som användes för att generera indexen.

### ETO_RTLREADING {#ETO-RTLREADING}
```
public static final int ETO_RTLREADING
```


Denna bit indikerar att texten MÅSTE läggas ut i högra‑till‑vänstra läsordning, istället för standardvänstra‑till‑högra ordning. Detta SKALL endast tillämpas när teckensnittet som valts i uppspelningsenhetens kontext är antingen hebreiska eller arabiska.

### ETO_NO_RECT {#ETO-NO-RECT}
```
public static final int ETO_NO_RECT
```


Denna bit indikerar att posten inte specificerar en avgränsande rektangel för textutmatningen.

### ETO_SMALL_CHARS {#ETO-SMALL-CHARS}
```
public static final int ETO_SMALL_CHARS
```


Denna bit indikerar att koderna för tecken i en utmatningssträng är 8‑bitars, härledda från de låga byten i 16‑bitars Unicode UTF16‑LE‑teckenkoder, där den högre byten antas vara 0.

### ETO_NUMERICSLOCAL {#ETO-NUMERICSLOCAL}
```
public static final int ETO_NUMERICSLOCAL
```


Denna bit indikerar att för att visa siffror bör lokalanpassade tecken användas.

### ETO_NUMERICSLATIN {#ETO-NUMERICSLATIN}
```
public static final int ETO_NUMERICSLATIN
```


Denna bit indikerar att för att visa siffror bör europeiska siffror användas.

### ETO_IGNORELANGUAGE {#ETO-IGNORELANGUAGE}
```
public static final int ETO_IGNORELANGUAGE
```


Denna bit indikerar att ingen speciell operativsystembehandling för glyfplacering ska utföras på högra‑till‑vänstra strängar; det vill säga, all glyfpositionering SKALL hanteras av rit‑ och tillståndsposter i metafilen.

### ETO_PDY {#ETO-PDY}
```
public static final int ETO_PDY
```


Denna bit indikerar att både horisontella och vertikala teckenförskjutningsvärden SKALL tillhandahållas.

### ETO_REVERSE_INDEX_MAP {#ETO-REVERSE-INDEX-MAP}
```
public static final int ETO_REVERSE_INDEX_MAP
```


Denna bit är reserverad och SKALL INTE användas.


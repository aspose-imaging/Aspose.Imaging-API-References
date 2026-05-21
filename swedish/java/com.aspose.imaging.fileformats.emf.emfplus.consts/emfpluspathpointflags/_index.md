---
title: "EmfPlusPathPointFlags"
second_title: "Aspose.Imaging för Java API-referens"
description: "Ett 32‑bitars osignerat heltal som specificerar hur punkterna och tillhörande puntktyper som definieras av detta objekt ska tolkas."
type: docs
weight: 38
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPathPointFlags extends System.Enum
```

En 32-bitars osignerad heltal som specificerar hur punkterna och tillhörande puntstyper som definieras av detta objekt ska tolkas. C (1 bit): Om satt, specificerar PathPoints‑arrayen absoluta positioner i koordinatrymden med 16‑bitars heltalskoordinater. Om rensad, specificerar PathPoints‑arrayen absoluta positioner i koordinatrymden med 32‑bitars flyttalskoordinater. Obs! Om P‑flaggan (nedan) är satt, kan denna flagga vara rensad och MUST ignoreras. R (1 bit): Om satt, specificeras puntstyperna i PathPointTypes‑arrayen av EmfPlusPathPointTypeRle‑objekt (avsnitt 2.2.2.32), som använder run‑length encoding (RLE)‑komprimering, och/eller EmfPlusPathPointType‑objekt (avsnitt 2.2.2.31). Se [MS-WMF] avsnitt 3.1.6 för mer information om RLE‑komprimering. Om rensad, specificeras puntstyperna i PathPointTypes‑arrayen av EmfPlusPathPointType‑objekt. P (1 bit): Om satt, specificerar varje element i PathPoints‑arrayen en position i koordinatrymden som är relativ till positionen som anges av föregående element i arrayen. För det första elementet i PathPoints antas en föregående position med koordinaterna (0,0). Om rensad, specificerar varje element i PathPoints‑arrayen en absolut position.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [C](#C) | c‑flaggan |
| [R](#R) | r‑flaggan |
| [P](#P) | p‑flaggan |
### C {#C}
```
public static final short C
```


c‑flaggan

### R {#R}
```
public static final short R
```


r‑flaggan

### P {#P}
```
public static final short P
```


p‑flaggan


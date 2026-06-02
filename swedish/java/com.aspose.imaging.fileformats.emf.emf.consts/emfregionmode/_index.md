---
title: "EmfRegionMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "RegionMode‑enumerationen definierar värden som används med EMR_SELECTCLIPPATH och EMR_EXTSELECTCLIPRGN för att specificera den aktuella vägen eller ett nytt område som kombineras med det aktuella klippområdet."
type: docs
weight: 39
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRegionMode extends System.Enum
```

RegionMode‑uppräkningen definierar värden som används med EMR\_SELECTCLIPPATH och EMR\_EXTSELECTCLIPRGN, och specificerar den aktuella banan eller en ny region som kombineras med den nuvarande klippregionen.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [RGN_AND](#RGN-AND) | Det nya klippområdet inkluderar skärningen (överlappande områden) av det aktuella klippområdet och den aktuella vägen (eller det nya området). |
| [RGN_OR](#RGN-OR) | Den nya beskärningsregionen inkluderar unionen (kombinerade områden) av den aktuella beskärningsregionen och den aktuella banan (eller ny region). |
| [RGN_XOR](#RGN-XOR) | Den nya beskärningsregionen inkluderar unionen av den aktuella beskärningsregionen och den aktuella banan (eller ny region) men utan de överlappande områdena. |
| [RGN_DIFF](#RGN-DIFF) | Den nya beskärningsregionen inkluderar områdena i den aktuella beskärningsregionen med de från den aktuella banan (eller ny region) uteslutna. |
| [RGN_COPY](#RGN-COPY) | Den nya beskärningsregionen är den aktuella banan (eller den nya regionen). |
### RGN_AND {#RGN-AND}
```
public static final int RGN_AND
```


Det nya klippområdet inkluderar skärningen (överlappande områden) av det aktuella klippområdet och den aktuella vägen (eller det nya området).

### RGN_OR {#RGN-OR}
```
public static final int RGN_OR
```


Den nya beskärningsregionen inkluderar unionen (kombinerade områden) av den aktuella beskärningsregionen och den aktuella banan (eller ny region).

### RGN_XOR {#RGN-XOR}
```
public static final int RGN_XOR
```


Den nya beskärningsregionen inkluderar unionen av den aktuella beskärningsregionen och den aktuella banan (eller ny region) men utan de överlappande områdena.

### RGN_DIFF {#RGN-DIFF}
```
public static final int RGN_DIFF
```


Den nya beskärningsregionen inkluderar områdena i den aktuella beskärningsregionen med de från den aktuella banan (eller ny region) uteslutna.

### RGN_COPY {#RGN-COPY}
```
public static final int RGN_COPY
```


Den nya beskärningsregionen är den aktuella banan (eller den nya regionen).


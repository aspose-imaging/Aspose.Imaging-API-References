---
title: "EmfRop4"
second_title: "Aspose.Imaging för Java API-referens"
description: "En kvartenär rasteroperation som specificerar ternära rasteroperationer för förgrunds- och bakgrundsfärgerna i en bitmap."
type: docs
weight: 110
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfrop4/
---
**Inheritance:**
java.lang.Object
```
public final class EmfRop4
```

En kvartenär rasteroperation som specificerar ternära rasteroperationer för förgrunds- och bakgrundsfärgerna i en bitmap. Dessa värden definierar hur färgdata från källrektangeln ska kombineras med färgdata från destinationsrektangeln.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfRop4(int dwordData)](#EmfRop4-int-) | Initierar en ny instans av klassen `EmfRop4`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBackgroundRop3()](#getBackgroundRop3--) | Hämtar bakgrunds‑ROP3. |
| [getForegroundRop3()](#getForegroundRop3--) | Hämtar förgrunds‑ROP3. |
### EmfRop4(int dwordData) {#EmfRop4-int-}
```
public EmfRop4(int dwordData)
```


Initierar en ny instans av klassen `EmfRop4`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dwordData | int | dword‑data. |

### getBackgroundRop3() {#getBackgroundRop3--}
```
public byte getBackgroundRop3()
```


Hämtar bakgrunds‑ROP3. De 8 mest signifikanta, osignerade bitarna i ett 24‑bitars ternärt rasteroperationsvärde från WMF Ternary Raster Operation‑enumerationen ([MS-WMF] avsnitt 2.1.1.31). Denna kod definierar hur bakgrundsfärgsdata från käll‑ och destinationsbitmapar samt penselmönster kombineras.

Värde: Bakgrunds‑ROP3.

**Returns:**
byte
### getForegroundRop3() {#getForegroundRop3--}
```
public byte getForegroundRop3()
```


Hämtar förgrunds‑ROP3. De 8 mest signifikanta, osignerade bitarna i ett 24‑bitars ternärt rasteroperationsvärde från WMF Ternary Raster Operation‑enumerationen. Denna kod definierar hur förgrundsfärgsdata från käll‑ och destinationsbitmapar samt penselmönster kombineras.

Värde: Förgrunds‑ROP3.

**Returns:**
byte

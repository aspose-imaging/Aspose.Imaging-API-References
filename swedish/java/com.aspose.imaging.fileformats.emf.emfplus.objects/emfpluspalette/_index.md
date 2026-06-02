---
title: "EmfPlusPalette"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusPalette-objektet specificerar färgerna som utgör en palett."
type: docs
weight: 57
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPalette extends EmfPlusStructureObjectType
```

EmfPlusPalette-objektet specificerar färgerna som utgör en palett.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusPalette()](#EmfPlusPalette--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPaletteStyleFlags()](#getPaletteStyleFlags--) | Hämtar eller anger palettens stilflaggor. |
| [setPaletteStyleFlags(int value)](#setPaletteStyleFlags-int-) | Hämtar eller anger palettens stilflaggor. |
| [getArgb32Entries()](#getArgb32Entries--) | Hämtar eller anger palettens poster. |
| [setArgb32Entries(int[] value)](#setArgb32Entries-int---) | Hämtar eller anger palettens poster. |
### EmfPlusPalette() {#EmfPlusPalette--}
```
public EmfPlusPalette()
```


### getPaletteStyleFlags() {#getPaletteStyleFlags--}
```
public int getPaletteStyleFlags()
```


Hämtar eller anger palettens stilflaggor.

Värde: PaletteStyleFlags (4 byte): Ett 32‑bitars osignerat heltal som specificerar attributen för data i paletten. Detta värde MÅSTE bestå av `EmfPlusPaletteStyleFlags`‑flaggor.

**Returns:**
int
### setPaletteStyleFlags(int value) {#setPaletteStyleFlags-int-}
```
public void setPaletteStyleFlags(int value)
```


Hämtar eller anger palettens stilflaggor.

Värde: PaletteStyleFlags (4 byte): Ett 32‑bitars osignerat heltal som specificerar attributen för data i paletten. Detta värde MÅSTE bestå av `EmfPlusPaletteStyleFlags`‑flaggor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Hämtar eller anger palettens poster.

Värde: PaletteEntries (variabel): En array av PaletteCount 32‑bitars ARGB‑objekt som specificerar data i paletten.

**Returns:**
int[] – Kopian av palettens poster.
### setArgb32Entries(int[] value) {#setArgb32Entries-int---}
```
public void setArgb32Entries(int[] value)
```


Hämtar eller anger palettens poster.

Värde: PaletteEntries (variabel): En array av PaletteCount 32‑bitars ARGB‑objekt som specificerar data i paletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |


---
title: "EmfPlusPalette"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusPalette-Objekt gibt die Farben an, aus denen eine Palette besteht."
type: docs
weight: 57
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPalette extends EmfPlusStructureObjectType
```

Das EmfPlusPalette-Objekt gibt die Farben an, aus denen eine Palette besteht.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusPalette()](#EmfPlusPalette--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPaletteStyleFlags()](#getPaletteStyleFlags--) | Liest oder setzt die Palette‑Stil‑Flags. |
| [setPaletteStyleFlags(int value)](#setPaletteStyleFlags-int-) | Liest oder setzt die Palette‑Stil‑Flags. |
| [getArgb32Entries()](#getArgb32Entries--) | Liest oder setzt die Paletteneinträge. |
| [setArgb32Entries(int[] value)](#setArgb32Entries-int---) | Liest oder setzt die Paletteneinträge. |
### EmfPlusPalette() {#EmfPlusPalette--}
```
public EmfPlusPalette()
```


### getPaletteStyleFlags() {#getPaletteStyleFlags--}
```
public int getPaletteStyleFlags()
```


Liest oder setzt die Palette‑Stil‑Flags.

Wert: PaletteStyleFlags (4 Bytes): Eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Attribute der Daten in der Palette angibt. Dieser Wert MUST aus `EmfPlusPaletteStyleFlags`‑Flags bestehen.

**Returns:**
int
### setPaletteStyleFlags(int value) {#setPaletteStyleFlags-int-}
```
public void setPaletteStyleFlags(int value)
```


Liest oder setzt die Palette‑Stil‑Flags.

Wert: PaletteStyleFlags (4 Bytes): Eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Attribute der Daten in der Palette angibt. Dieser Wert MUST aus `EmfPlusPaletteStyleFlags`‑Flags bestehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Liest oder setzt die Paletteneinträge.

Wert: PaletteEntries (variabel): Ein Array von PaletteCount 32‑Bit‑ARGB‑Objekten, die die Daten in der Palette angeben.

**Returns:**
int[] – Die Kopie der Paletteneinträge.
### setArgb32Entries(int[] value) {#setArgb32Entries-int---}
```
public void setArgb32Entries(int[] value)
```


Liest oder setzt die Paletteneinträge.

Wert: PaletteEntries (variabel): Ein Array von PaletteCount 32‑Bit‑ARGB‑Objekten, die die Daten in der Palette angeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |


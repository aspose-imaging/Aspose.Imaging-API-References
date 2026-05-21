---
title: "EmfUniversalFontId"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das UniversalFontId-Objekt definiert einen Mechanismus zur Identifizierung von Schriftarten in EMF-Metadateien."
type: docs
weight: 37
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfUniversalFontId extends EmfObject
```

Das UniversalFontId-Objekt definiert einen Mechanismus zur Identifizierung von Schriftarten in EMF-Metadateien.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfUniversalFontId()](#EmfUniversalFontId--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getChecksum()](#getChecksum--) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Prüfsumme der Schriftart ist. |
| [setChecksum(int value)](#setChecksum-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Prüfsumme der Schriftart ist. |
| [getIndex()](#getIndex--) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die einen Index darstellt, der dem Schriftart‑Objekt zugeordnet ist. |
| [setIndex(int value)](#setIndex-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die einen Index darstellt, der dem Schriftart‑Objekt zugeordnet ist. |
### EmfUniversalFontId() {#EmfUniversalFontId--}
```
public EmfUniversalFontId()
```


### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Prüfsumme der Schriftart ist. Der Prüfsummenwert hat die folgenden Bedeutungen. 0x00000000 Das Objekt ist eine Geräteschrift. 0x00000001 Das Objekt ist eine Type‑1‑Schrift, die auf dem Client‑Rechner installiert wurde und vom PostScript‑Druckertreiber als Geräteschrift aufgelistet wird. 0x00000002 Das Objekt ist keine Schrift, sondern ein Type‑1‑Rasterisierer. 3 \u2264 value Das Objekt ist ein Bitmap-, Vektor- oder TrueType‑Font bzw. ein Type‑1‑rasterisierter Font, der von einem Type‑1‑Rasterisierer erstellt wurde.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Prüfsumme der Schriftart ist. Der Prüfsummenwert hat die folgenden Bedeutungen. 0x00000000 Das Objekt ist eine Geräteschrift. 0x00000001 Das Objekt ist eine Type‑1‑Schrift, die auf dem Client‑Rechner installiert wurde und vom PostScript‑Druckertreiber als Geräteschrift aufgelistet wird. 0x00000002 Das Objekt ist keine Schrift, sondern ein Type‑1‑Rasterisierer. 3 \u2264 value Das Objekt ist ein Bitmap-, Vektor- oder TrueType‑Font bzw. ein Type‑1‑rasterisierter Font, der von einem Type‑1‑Rasterisierer erstellt wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getIndex() {#getIndex--}
```
public int getIndex()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die einen Index darstellt, der dem Schriftart‑Objekt zugeordnet ist. Die Bedeutung dieses Feldes wird durch den Schrifttyp bestimmt.

**Returns:**
int
### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die einen Index darstellt, der dem Schriftart‑Objekt zugeordnet ist. Die Bedeutung dieses Feldes wird durch den Schrifttyp bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |


---
title: "WmfSetMapperFlags"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der META_SETMAPPERFLAGS‑Datensatz definiert den Algorithmus, den der Schriftarten‑Mapper verwendet, wenn er logische Schriften auf physische Schriften abbildet."
type: docs
weight: 78
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfSetMapperFlags extends WmfObject
```

Der META\_SETMAPPERFLAGS-Datensatz definiert den Algorithmus, den der Font-Mapper verwendet, wenn er logische Schriften auf physische Schriften abbildet.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfSetMapperFlags()](#WmfSetMapperFlags--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMapperValues()](#getMapperValues--) | Liest oder setzt die Mapper‑Werte. |
| [setMapperValues(int value)](#setMapperValues-int-) | Liest oder setzt die Mapper‑Werte. |
### WmfSetMapperFlags() {#WmfSetMapperFlags--}
```
public WmfSetMapperFlags()
```


### getMapperValues() {#getMapperValues--}
```
public int getMapperValues()
```


Liest oder setzt die Mapper‑Werte.

Wert: Der Schriftarten‑Mapper versucht, das Seitenverhältnis einer Schrift an das aktuelle Geräte‑Seitenverhältnis anzupassen. Wenn Bit Null gesetzt ist, wählt der Mapper nur passende Schriften aus.

**Returns:**
int
### setMapperValues(int value) {#setMapperValues-int-}
```
public void setMapperValues(int value)
```


Liest oder setzt die Mapper‑Werte.

Wert: Der Schriftarten‑Mapper versucht, das Seitenverhältnis einer Schrift an das aktuelle Geräte‑Seitenverhältnis anzupassen. Wenn Bit Null gesetzt ist, wählt der Mapper nur passende Schriften aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |


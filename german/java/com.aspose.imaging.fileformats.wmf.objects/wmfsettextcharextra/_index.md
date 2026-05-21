---
title: "WmfSetTextCharExtra"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der META_SETTEXTCHAREXTRA-Datensatz definiert den Zeichenabstand für die Textausrichtung im Wiedergabegerätekontext."
type: docs
weight: 86
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfsettextcharextra/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfSetTextCharExtra extends WmfObject
```

Der META\_SETTEXTCHAREXTRA-Datensatz definiert den Zeichenabstand für die Textausrichtung im Wiedergabegerätekontext. Der Abstand wird dem Leerraum zwischen jedem Zeichen hinzugefügt, einschließlich ``‑Zeichen, wenn eine Zeile mit Blocksatz ausgegeben wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfSetTextCharExtra()](#WmfSetTextCharExtra--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCharExtra()](#getCharExtra--) | Liest oder setzt den zusätzlichen Zeichenabstand. |
| [setCharExtra(int value)](#setCharExtra-int-) | Liest oder setzt den zusätzlichen Zeichenabstand. |
### WmfSetTextCharExtra() {#WmfSetTextCharExtra--}
```
public WmfSetTextCharExtra()
```


### getCharExtra() {#getCharExtra--}
```
public int getCharExtra()
```


Liest oder setzt den zusätzlichen Zeichenabstand.

Wert: Die Menge des zusätzlichen Abstands in logischen Einheiten, die jedem Zeichen hinzugefügt wird. Wenn der aktuelle Abbildungsmodus nicht MM\_TEXT ist, wird dieser Wert transformiert und auf den nächsten Pixel gerundet. Einzelheiten zum Festlegen des Abbildungsmodus finden Sie in META\_SETMAPMODE (Abschnitt 2.3.5.17).

**Returns:**
int
### setCharExtra(int value) {#setCharExtra-int-}
```
public void setCharExtra(int value)
```


Liest oder setzt den zusätzlichen Zeichenabstand.

Wert: Die Menge des zusätzlichen Abstands in logischen Einheiten, die jedem Zeichen hinzugefügt wird. Wenn der aktuelle Abbildungsmodus nicht MM\_TEXT ist, wird dieser Wert transformiert und auf den nächsten Pixel gerundet. Einzelheiten zum Festlegen des Abbildungsmodus finden Sie in META\_SETMAPMODE (Abschnitt 2.3.5.17).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |


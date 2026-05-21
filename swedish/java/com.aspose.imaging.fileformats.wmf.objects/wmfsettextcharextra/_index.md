---
title: "WmfSetTextCharExtra"
second_title: "Aspose.Imaging för Java API-referens"
description: "META_SETTEXTCHAREXTRA-posten definierar teckenavstånd mellan tecken för textjustering i uppspelningsenhetens kontext."
type: docs
weight: 86
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmfsettextcharextra/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetTextCharExtra extends WmfObject
```

META\_SETTEXTCHAREXTRA-posten definierar teckenavstånd mellan tecken för textjustering i uppspelningsenhetens kontext. Avstånd läggs till i det vita utrymmet mellan varje tecken, inklusive ``-tecken, när en rad med justerad text skrivs ut.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfSetTextCharExtra()](#WmfSetTextCharExtra--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCharExtra()](#getCharExtra--) | Hämtar eller anger extra tecken. |
| [setCharExtra(int value)](#setCharExtra-int-) | Hämtar eller anger extra tecken. |
### WmfSetTextCharExtra() {#WmfSetTextCharExtra--}
```
public WmfSetTextCharExtra()
```


### getCharExtra() {#getCharExtra--}
```
public int getCharExtra()
```


Hämtar eller anger extra tecken.

Värde: Mängden extra utrymme, i logiska enheter, som ska läggas till varje tecken. Om det aktuella kartläggningsläget inte är MM\_TEXT, omvandlas detta värde och avrundas till närmaste pixel. För detaljer om hur kartläggningsläget ställs in, se META\_SETMAPMODE (avsnitt 2.3.5.17).

**Returns:**
int
### setCharExtra(int value) {#setCharExtra-int-}
```
public void setCharExtra(int value)
```


Hämtar eller anger extra tecken.

Värde: Mängden extra utrymme, i logiska enheter, som ska läggas till varje tecken. Om det aktuella kartläggningsläget inte är MM\_TEXT, omvandlas detta värde och avrundas till närmaste pixel. För detaljer om hur kartläggningsläget ställs in, se META\_SETMAPMODE (avsnitt 2.3.5.17).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |


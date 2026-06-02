---
title: "OdTextAlignModeFlags"
second_title: "Aspose.Imaging för Java API-referens"
description: "Flaggor för justeringsläge för text i öppet dokument."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.opendocument.enums/odtextalignmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdTextAlignModeFlags extends System.Enum
```

Flaggor för justeringsläge för text i öppet dokument.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | Ritpositionen i uppspelningsenhetens kontext FÅR INTE uppdateras efter varje textutmatningsanrop. |
| [Left](#Left) | Referenspunkten MÅSTE ligga på den vänstra kanten av avgränsningsrektangeln. |
| [Top](#Top) | Referenspunkten MÅSTE ligga på den övre kanten av avgränsningsrektangeln. |
| [Updatecp](#Updatecp) | Ritpositionen i uppspelningsenhetens kontext MÅSTE uppdateras efter varje textutmatningsanrop. |
| [Right](#Right) | Referenspunkten MÅSTE ligga på den högra kanten av avgränsningsrektangeln. |
| [Center](#Center) | Referenspunkten MÅSTE justeras horisontellt med mitten av den avgränsande rektangeln. |
| [Justify](#Justify) | Texten måste justeras så att varje textrad i ett stycke har samma längd. |
| [Bottom](#Bottom) | Referenspunkten MÅSTE ligga på den nedre kanten av avgränsningsrektangeln. |
| [Baseline](#Baseline) | Referenspunkten MÅSTE ligga på textens baslinje. |
| [Rtlreading](#Rtlreading) | Texten MÅSTE läggas ut i läsordning från höger till vänster, istället för standardordningen från vänster till höger. |
| [Horizontal](#Horizontal) | Represents Horizontal text align sets (Left | Right | Centrera) |
| [Vertical](#Vertical) | Represents Vertical text align sets (Top | Bottom | Baslinje) |
### Noupdatecp {#Noupdatecp}
```
public static final int Noupdatecp
```


Ritpositionen i uppspelningsenhetens kontext FÅR INTE uppdateras efter varje textutmatningsanrop. Referenspunkten MÅSTE skickas till textutmatningsfunktionen.

### Left {#Left}
```
public static final int Left
```


Referenspunkten MÅSTE ligga på den vänstra kanten av avgränsningsrektangeln.

### Top {#Top}
```
public static final int Top
```


Referenspunkten MÅSTE ligga på den övre kanten av avgränsningsrektangeln.

### Updatecp {#Updatecp}
```
public static final int Updatecp
```


Ritpositionen i uppspelningsenhetens kontext MÅSTE uppdateras efter varje textutmatningsanrop. Den MÅSTE användas som referenspunkt.

### Right {#Right}
```
public static final int Right
```


Referenspunkten MÅSTE ligga på den högra kanten av avgränsningsrektangeln.

### Center {#Center}
```
public static final int Center
```


Referenspunkten MÅSTE justeras horisontellt med mitten av den avgränsande rektangeln.

### Justify {#Justify}
```
public static final int Justify
```


Texten måste justeras så att varje textrad i ett stycke har samma längd.

### Bottom {#Bottom}
```
public static final int Bottom
```


Referenspunkten MÅSTE ligga på den nedre kanten av avgränsningsrektangeln.

### Baseline {#Baseline}
```
public static final int Baseline
```


Referenspunkten MÅSTE ligga på textens baslinje.

### Rtlreading {#Rtlreading}
```
public static final int Rtlreading
```


Texten MÅSTE läggas ut i läsordning från höger till vänster, istället för standardordningen från vänster till höger. Detta BÖR endast tillämpas när typsnittet som definieras i uppspelningsenhetens kontext är antingen hebreiska eller arabiska.

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Representerar horisontella textjusteringsuppsättningar (Vänster | Höger | Centrera)

### Vertical {#Vertical}
```
public static final int Vertical
```


Representerar vertikala textjusteringsuppsättningar (Topp | Botten | Baslinje)


---
title: "WmfTextAlignmentModeFlags"
second_title: "Aspose.Imaging för Java API-referens"
description: "TextAlignmentMode Flags specificerar förhållandet mellan en referenspunkt och en avgränsande rektangel för textjustering."
type: docs
weight: 36
url: /sv/java/com.aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfTextAlignmentModeFlags extends System.Enum
```

TextAlignmentMode Flags specificerar förhållandet mellan en referenspunkt och en avgränsande rektangel för textjustering. Dessa flaggor kan kombineras för att ange flera alternativ, med restriktionen att endast en flagga kan väljas som ändrar ritpositionen i uppspelningsenhetens kontext. Horisontell textjustering utförs när typsnittet har en horisontell standardbaslinje.

--------------------

TextAlignmentMode flags specificerar tre olika komponenter av textjustering: - Den horisontella positionen för referenspunkten bestäms av TA\_RIGHT och TA\_CENTER; om dessa bitar är nollställda ska justeringen vara TA\_LEFT. - Den vertikala positionen för referenspunkten bestäms av TA\_BOTTOM och TA\_BASELINE; om dessa bitar är nollställda ska justeringen vara TA\_TOP. - Om utdata‑positionen i uppspelningsenhetens kontext ska uppdateras efter textutmatning bestäms av TA\_UPDATECP; om den biten är nollställd får positionen INTE uppdateras. Detta är orsaken till att tre olika nollvärden definieras i uppräkningen; de representerar standardtillstånden för de tre komponenterna av textjustering.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | Ritpositionen i uppspelningsenhetens kontext FÅR INTE uppdateras efter varje textutmatningsanrop. |
| [Left](#Left) | Referenspunkten MÅSTE ligga på den vänstra kanten av avgränsningsrektangeln. |
| [Top](#Top) | Referenspunkten MÅSTE ligga på den övre kanten av avgränsningsrektangeln. |
| [Updatecp](#Updatecp) | Ritpositionen i uppspelningsenhetens kontext MÅSTE uppdateras efter varje textutmatningsanrop. |
| [Right](#Right) | Referenspunkten MÅSTE ligga på den högra kanten av avgränsningsrektangeln. |
| [Center](#Center) | Referenspunkten MÅSTE justeras horisontellt med mitten av den avgränsande rektangeln. |
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


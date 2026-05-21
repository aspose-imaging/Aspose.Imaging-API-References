---
title: "OdGradientStyle"
second_title: "Aspose.Imaging för Java API-referens"
description: "Gradientstilen"
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.opendocument.enums/odgradientstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdGradientStyle extends System.Enum
```

Gradientstilen
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Axial](#Axial) | Den axial definierar ett bilinjärt gradient som också är känt som reflekterat gradient eller speglat linjärt gradient. |
| [Ellipsoid](#Ellipsoid) | Ellipsoiden definierar ett gradient där färgerna blandas längs radien från centrum av en ellipsoid som definieras med attributen draw:cx och draw:cy. |
| [Linear](#Linear) | Den linjära definierar ett gradient där färgerna blandas längs gradientens linjära axel. |
| [Radial](#Radial) | Den radiella definierar ett gradient där färgerna blandas längs radien från centrum av en cirkel som definieras med attributen draw:cx och draw:cy. |
| [Rectangle](#Rectangle) | Rektangeln definierar ett gradient som skapar en rektangulär blandning från rektangelns centrum till den kortaste av de fyra kanterna. |
| [Square](#Square) | Fyrkanten definierar ett gradient som skapar en fyrkantig blandning, som efterliknar den visuella perspektivet i en korridor eller fågelperspektivet av en pyramid. |
| [None](#None) | Gradientstilen är ingen |
### Axial {#Axial}
```
public static final int Axial
```


Den axial definierar ett bilinjärt gradient som också är känt som reflekterat gradient eller speglat linjärt gradient. Det skapas som ett linjärt gradient som är speglat (eller reflekterat) längs sin axel.

### Ellipsoid {#Ellipsoid}
```
public static final int Ellipsoid
```


Ellipsoiden definierar ett gradient där färgerna blandas längs radien från centrum av en ellipsoid som definieras med attributen draw:cx och draw:cy. Längden på den semi major-axeln är bredden på det fyllda området och längden på den semi-minor.

### Linear {#Linear}
```
public static final int Linear
```


Den linjära definierar ett gradient där färgerna blandas längs gradientens linjära axel. Gradientens axel specificeras med attributet draw:angle medurs mot den vertikala axeln.

### Radial {#Radial}
```
public static final int Radial
```


Den radiella definierar ett gradient där färgerna blandas längs radien från centrum av en cirkel som definieras med attributen draw:cx och draw:cy. Yttre delen av cirkeln fylls med slutfärgen.

### Rectangle {#Rectangle}
```
public static final int Rectangle
```


Rektangeln definierar ett gradient som skapar en rektangulär blandning från rektangelns centrum till den kortaste av de fyra kanterna. Rektangelns centrum definieras med attributen draw:cx och draw:cy. Rektangelns bredd är bredden på det fyllda området, rektangelns höjd är höjden på det fyllda området. Yttre delen av fyrkanten fylls med slutfärgen.

### Square {#Square}
```
public static final int Square
```


Fyrkanten definierar ett gradient som skapar en fyrkantig blandning, som efterliknar det visuella perspektivet i en korridor eller fågelperspektivet av en pyramid. Även känd som "box gradient" och "pyramidal gradient". Fyrkantens centrum definieras med attributen draw:cx och draw:cy. Fyrkantens bredd och höjd är det minsta värdet av antingen bredden eller höjden på det fyllda området. Yttre delen av fyrkanten fylls med slutfärgen.

### None {#None}
```
public static final int None
```


Gradientstilen är ingen


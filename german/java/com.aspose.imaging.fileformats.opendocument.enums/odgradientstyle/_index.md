---
title: "OdGradientStyle"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Verlaufstil"
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.opendocument.enums/odgradientstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdGradientStyle extends System.Enum
```

Der Verlaufstil
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Axial](#Axial) | Der axiale definiert einen bilinearen Farbverlauf, der auch als reflektierter Farbverlauf oder gespiegelter linearer Farbverlauf bekannt ist. |
| [Ellipsoid](#Ellipsoid) | Der Ellipsoid definiert einen Farbverlauf, bei dem die Farben entlang des Radius vom Zentrum eines Ellipsoids gemischt werden, wie mit den Attributen draw:cx und draw:cy definiert. |
| [Linear](#Linear) | Der lineare definiert einen Farbverlauf, bei dem die Farben entlang der linearen Achse des Farbverlaufs gemischt werden. |
| [Radial](#Radial) | Der radiale definiert einen Farbverlauf, bei dem die Farben entlang des Radius vom Zentrum eines Kreises gemischt werden, wie mit den Attributen draw:cx und draw:cy definiert. |
| [Rectangle](#Rectangle) | Das Rechteck definiert einen Farbverlauf, der eine rechteckige Mischung vom Zentrum des Rechtecks bis zur kürzesten der vier Kanten erzeugt. |
| [Square](#Square) | Das Quadrat definiert einen Farbverlauf, der eine quadratische Mischung erzeugt und die visuelle Perspektive in einem Korridor oder die Luftansicht einer Pyramide nachahmt. |
| [None](#None) | Der Farbverlaufsstil ist keiner. |
### Axial {#Axial}
```
public static final int Axial
```


Der axiale definiert einen bilinearen Farbverlauf, der auch als reflektierter Farbverlauf oder gespiegelter linearer Farbverlauf bekannt ist. Er wird als linearer Farbverlauf erstellt, der entlang seiner Achse gespiegelt (oder reflektiert) wird.

### Ellipsoid {#Ellipsoid}
```
public static final int Ellipsoid
```


Der Ellipsoid definiert einen Farbverlauf, bei dem die Farben entlang des Radius vom Zentrum eines Ellipsoids gemischt werden, wie mit den Attributen draw:cx und draw:cy definiert. Die Länge der halb‑großen Achse ist die Breite des gefüllten Bereichs und die Länge der halb‑kleinen Achse.

### Linear {#Linear}
```
public static final int Linear
```


Der lineare definiert einen Farbverlauf, bei dem die Farben entlang der linearen Achse des Farbverlaufs gemischt werden. Die Achse des Farbverlaufs wird mit dem Attribut draw:angle im Uhrzeigersinn zur vertikalen Achse angegeben.

### Radial {#Radial}
```
public static final int Radial
```


Der radiale definiert einen Farbverlauf, bei dem die Farben entlang des Radius vom Zentrum eines Kreises gemischt werden, wie mit den Attributen draw:cx und draw:cy definiert. Der Außenbereich des Kreises wird mit der Endfarbe gefüllt.

### Rectangle {#Rectangle}
```
public static final int Rectangle
```


Das Rechteck definiert einen Farbverlauf, der eine rechteckige Mischung vom Zentrum des Rechtecks bis zur kürzesten der vier Kanten erzeugt. Das Zentrum des Rechtecks wird mit den Attributen draw:cx und draw:cy definiert. Die Breite des Rechtecks entspricht der Breite des gefüllten Bereichs, die Höhe des Rechtecks entspricht der Höhe des gefüllten Bereichs. Der Außenbereich des Quadrats wird mit der Endfarbe gefüllt.

### Square {#Square}
```
public static final int Square
```


Das Quadrat definiert einen Farbverlauf, der eine quadratische Mischung erzeugt und die visuelle Perspektive in einem Korridor oder die Luftansicht einer Pyramide nachahmt. Auch bekannt als „Box‑Gradient“ und „Pyramiden‑Gradient“. Das Zentrum des Quadrats wird mit den Attributen draw:cx und draw:cy definiert. Breite und Höhe des Quadrats entsprechen dem kleineren Wert von Breite oder Höhe des gefüllten Bereichs. Der Außenbereich des Quadrats wird mit der Endfarbe gefüllt.

### None {#None}
```
public static final int None
```


Der Farbverlaufsstil ist keiner.


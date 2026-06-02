---
title: "OdGradientStyle"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Lo stile del gradiente"
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.opendocument.enums/odgradientstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdGradientStyle extends System.Enum
```

Lo stile del gradiente
## Campi

| Campo | Descrizione |
| --- | --- |
| [Axial](#Axial) | L'axial definisce un gradiente bi-lineare noto anche come gradiente riflesso o gradiente lineare specchiato. |
| [Ellipsoid](#Ellipsoid) | L'ellipsoid definisce un gradiente in cui i colori si mescolano lungo il raggio dal centro di un ellipsoid come definito con gli attributi draw:cx e draw:cy. |
| [Linear](#Linear) | Il linear definisce un gradiente in cui i colori si mescolano lungo l'asse lineare del gradiente. |
| [Radial](#Radial) | Il radial definisce un gradiente in cui i colori si mescolano lungo il raggio dal centro di un cerchio come definito con gli attributi draw:cx e draw:cy. |
| [Rectangle](#Rectangle) | Il rectangle definisce un gradiente che produce una sfumatura rettangolare dal centro del rettangolo al lato più corto dei 4 bordi. |
| [Square](#Square) | Il square definisce un gradiente che produce una sfumatura quadrata, imitazione della prospettiva visiva in un corridoio o della vista aerea di una piramide. |
| [None](#None) | Lo stile del gradiente è nessuno. |
### Axial {#Axial}
```
public static final int Axial
```


L'axial definisce un gradiente bi-lineare noto anche come gradiente riflesso o gradiente lineare specchiato. Viene creato come un gradiente lineare che è specchiato (o riflesso) lungo il suo asse.

### Ellipsoid {#Ellipsoid}
```
public static final int Ellipsoid
```


L'ellipsoid definisce un gradiente in cui i colori si mescolano lungo il raggio dal centro di un ellipsoid come definito con gli attributi draw:cx e draw:cy. La lunghezza del semi-asse maggiore è la larghezza dell'area riempita e la lunghezza del semi-asse minore

### Linear {#Linear}
```
public static final int Linear
```


Il linear definisce un gradiente in cui i colori si mescolano lungo l'asse lineare del gradiente. L'asse del gradiente è specificato con l'attributo draw:angle in senso orario rispetto all'asse verticale.

### Radial {#Radial}
```
public static final int Radial
```


Il radial definisce un gradiente in cui i colori si mescolano lungo il raggio dal centro di un cerchio come definito con gli attributi draw:cx e draw:cy. L'esterno del cerchio è riempito con il colore finale.

### Rectangle {#Rectangle}
```
public static final int Rectangle
```


Il rectangle definisce un gradiente che produce una sfumatura rettangolare dal centro del rettangolo al lato più corto dei 4 bordi. Il centro del rettangolo è definito con gli attributi draw:cx e draw:cy. La larghezza del rettangolo è la larghezza dell'area riempita, l'altezza del rettangolo è l'altezza dell'area riempita. L'esterno del quadrato è riempito con il colore finale.

### Square {#Square}
```
public static final int Square
```


Il square definisce un gradiente che produce una sfumatura quadrata, imitazione della prospettiva visiva in un corridoio o della vista aerea di una piramide. Conosciuto anche come \"box gradient\" e \"pyramidal gradient\". Il centro del quadrato è definito con gli attributi draw:cx e draw:cy. La larghezza e l'altezza del quadrato corrispondono al valore minimo tra la larghezza o l'altezza dell'area riempita. L'esterno del quadrato è riempito con il colore finale.

### None {#None}
```
public static final int None
```


Lo stile del gradiente è nessuno.


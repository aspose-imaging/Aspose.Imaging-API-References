---
title: "OdGradientStyle"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Gradyan stili"
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.opendocument.enums/odgradientstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdGradientStyle extends System.Enum
```

Gradyan stili
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Axial](#Axial) | Axial, yansıtılmış degrade veya yansıtılmış doğrusal degrade olarak da bilinen çift doğrusal bir degrade tanımlar. |
| [Ellipsoid](#Ellipsoid) | Elipsoit, renklerin draw:cx ve draw:cy öznitelikleriyle tanımlanan bir elipsoidin merkezinden yarıçapa doğru karıştığı bir degrade tanımlar. |
| [Linear](#Linear) | Doğrusal, renklerin degrade'nin doğrusal ekseni boyunca karıştığı bir degrade tanımlar. |
| [Radial](#Radial) | Radial, renklerin draw:cx ve draw:cy öznitelikleriyle tanımlanan bir dairenin merkezinden yarıçapa doğru karıştığı bir degrade tanımlar. |
| [Rectangle](#Rectangle) | Dikdörtgen, dikdörtgenin merkezinden dört kenarın en kısasına doğru dikdörtgen bir karışım üreten bir degrade tanımlar. |
| [Square](#Square) | Kare, bir koridordaki görsel perspektifi veya bir piramidin kuşbakışı görünümünü taklit eden kare bir karışım üreten bir degrade tanımlar. |
| [None](#None) | Degrade stili yok |
### Axial {#Axial}
```
public static final int Axial
```


Axial, yansıtılmış degrade veya yansıtılmış doğrusal degrade olarak da bilinen çift doğrusal bir degrade tanımlar. Bu, ekseni boyunca yansıtılmış (veya yansıtılmış) bir doğrusal degrade olarak oluşturulur.

### Ellipsoid {#Ellipsoid}
```
public static final int Ellipsoid
```


Elipsoit, renklerin draw:cx ve draw:cy öznitelikleriyle tanımlanan bir elipsoidin merkezinden yarıçapa doğru karıştığı bir degrade tanımlar. Yarı büyük eksenin uzunluğu doldurulan alanın genişliğidir ve yarı küçük eksenin uzunluğu

### Linear {#Linear}
```
public static final int Linear
```


Doğrusal, renklerin degrade'nin doğrusal ekseni boyunca karıştığı bir degrade tanımlar. Degrade ekseni, dik eksene göre saat yönünde draw:angle özniteliğiyle belirtilir.

### Radial {#Radial}
```
public static final int Radial
```


Radial, renklerin draw:cx ve draw:cy öznitelikleriyle tanımlanan bir dairenin merkezinden yarıçapa doğru karıştığı bir degrade tanımlar. Dairenin dış kısmı son renk ile doldurulur.

### Rectangle {#Rectangle}
```
public static final int Rectangle
```


Dikdörtgen, dikdörtgenin merkezinden dört kenarın en kısasına doğru dikdörtgen bir karışım üreten bir degrade tanımlar. Dikdörtgenin merkezi draw:cx ve draw:cy öznitelikleriyle tanımlanır. Dikdörtgenin genişliği doldurulan alanın genişliğidir, yüksekliği ise doldurulan alanın yüksekliğidir. Karenin dış kısmı son renk ile doldurulur.

### Square {#Square}
```
public static final int Square
```


Kare, bir koridordaki görsel perspektifi veya bir piramidin kuşbakışı görünümünü taklit eden kare bir karışım üreten bir degrade tanımlar. Ayrıca \"box gradient\" ve \"pyramidal gradient\" olarak da bilinir. Karenin merkezi draw:cx ve draw:cy öznitelikleriyle tanımlanır. Karenin genişliği ve yüksekliği, doldurulan alanın genişliği ya da yüksekliğinin en küçük değeridir. Karenin dış kısmı son renk ile doldurulur.

### None {#None}
```
public static final int None
```


Degrade stili yok


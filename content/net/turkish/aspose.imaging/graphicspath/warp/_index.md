---
title: Warp
second_title: Aspose.Imaging for .NET API Referansı
description: Buna bir dikdörtgen ve bir paralelkenar ile tanımlanan bir çarpıtma dönüşümü uygular.GraphicsPathaspose.imaging/graphicspath .
type: docs
weight: 180
url: /tr/aspose.imaging/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

Buna bir dikdörtgen ve bir paralelkenar ile tanımlanan bir çarpıtma dönüşümü uygular.[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| destPoints | PointF[] | bir dizi[`PointF`](../../pointf) tarafından tanımlanan dikdörtgenin bir paralelkenarı tanımlayan yapılar*srcRect* dönüştürülür. Dizi, üç veya dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ alt köşesi ilk üç nokta tarafından belirtilir. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef) tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden*destPoints*. |

### Ayrıca bakınız

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [GraphicsPath](../../graphicspath)
* ad alanı [Aspose.Imaging](../../graphicspath)
* toplantı [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Buna bir dikdörtgen ve bir paralelkenar ile tanımlanan bir çarpıtma dönüşümü uygular.[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| destPoints | PointF[] | bir dizi[`PointF`](../../pointf) tarafından tanımlanan dikdörtgenin bir paralelkenarı tanımlayan yapılar*srcRect* dönüştürülür. Dizi, üç veya dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ alt köşesi ilk üç nokta tarafından belirtilir. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef) tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix) bu, yola uygulanacak bir geometrik dönüşümü belirtir. |

### Ayrıca bakınız

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* class [GraphicsPath](../../graphicspath)
* ad alanı [Aspose.Imaging](../../graphicspath)
* toplantı [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Buna bir dikdörtgen ve bir paralelkenar ile tanımlanan bir çarpıtma dönüşümü uygular.[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| destPoints | PointF[] | bir dizi[`PointF`](../../pointf) tarafından tanımlanan dikdörtgenin bir paralelkenarı tanımlayan yapılar*srcRect* dönüştürülür. Dizi, üç veya dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ alt köşesi ilk üç nokta tarafından belirtilir. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef) tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix) bu, yola uygulanacak bir geometrik dönüşümü belirtir. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode) Bu çarpıtma işleminin perspektif mi yoksa çift doğrusal mod mu kullandığını belirten numaralandırma. |

### Ayrıca bakınız

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* ad alanı [Aspose.Imaging](../../graphicspath)
* toplantı [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Buna bir dikdörtgen ve bir paralelkenar ile tanımlanan bir çarpıtma dönüşümü uygular.[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| destPoints | PointF[] | bir dizi[`PointF`](../../pointf) tarafından tanımlanan dikdörtgenin bir paralelkenarı tanımlayan yapılar*srcRect* dönüştürülür. Dizi, üç veya dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ alt köşesi ilk üç nokta tarafından belirtilir. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef) tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix) bu, yola uygulanacak bir geometrik dönüşümü belirtir. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode) Bu çarpıtma işleminin perspektif mi yoksa çift doğrusal mod mu kullandığını belirten numaralandırma. |
| flatness | Single | Ortaya çıkan yolun ne kadar düz olduğunu belirten 0 ile 1 arasında bir değer. Daha fazla bilgi için bkz.[`Flatten`](../flatten) yöntemler. |

### Ayrıca bakınız

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* ad alanı [Aspose.Imaging](../../graphicspath)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

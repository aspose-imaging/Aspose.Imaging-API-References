---
title: Warp
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Applique une transformation warp définie par un rectangle et un parallélogramme à cetteGraphicsPathaspose.imaging/graphicspath .
type: docs
weight: 180
url: /fr/net/aspose.imaging/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

Applique une transformation warp, définie par un rectangle et un parallélogramme, à cette[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| destPoints | PointF[] | Un étalage de[`PointF`](../../pointf) structures qui définissent un parallélogramme auquel le rectangle défini par*srcRect* est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est impliqué par les trois premiers points. |
| srcRect | RectangleF | UN[`RectangleF`](../../rectanglef) qui représente le rectangle transformé en parallélogramme défini par*destPoints*. |

### Voir également

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [GraphicsPath](../../graphicspath)
* espace de noms [Aspose.Imaging](../../graphicspath)
* Assemblée [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Applique une transformation warp, définie par un rectangle et un parallélogramme, à cette[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| destPoints | PointF[] | Un étalage de[`PointF`](../../pointf) structures qui définissent un parallélogramme auquel le rectangle défini par*srcRect* est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est impliqué par les trois premiers points. |
| srcRect | RectangleF | UN[`RectangleF`](../../rectanglef) qui représente le rectangle transformé en parallélogramme défini par*destPoints*. |
| matrix | Matrix | UN[`Matrix`](../../matrix) qui spécifie une transformation géométrique à appliquer au chemin. |

### Voir également

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* class [GraphicsPath](../../graphicspath)
* espace de noms [Aspose.Imaging](../../graphicspath)
* Assemblée [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Applique une transformation warp, définie par un rectangle et un parallélogramme, à cette[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| destPoints | PointF[] | Un étalage de[`PointF`](../../pointf) structures qui définissent un parallélogramme auquel le rectangle défini par*srcRect* est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est impliqué par les trois premiers points. |
| srcRect | RectangleF | UN[`RectangleF`](../../rectanglef) qui représente le rectangle transformé en parallélogramme défini par*destPoints*. |
| matrix | Matrix | UN[`Matrix`](../../matrix) qui spécifie une transformation géométrique à appliquer au chemin. |
| warpMode | WarpMode | UN[`WarpMode`](../../warpmode) énumération qui spécifie si cette opération de déformation utilise le mode perspective ou bilinéaire. |

### Voir également

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* espace de noms [Aspose.Imaging](../../graphicspath)
* Assemblée [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Applique une transformation warp, définie par un rectangle et un parallélogramme, à cette[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| destPoints | PointF[] | Un étalage de[`PointF`](../../pointf) structures qui définissent un parallélogramme auquel le rectangle défini par*srcRect* est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est impliqué par les trois premiers points. |
| srcRect | RectangleF | UN[`RectangleF`](../../rectanglef) qui représente le rectangle transformé en parallélogramme défini par*destPoints*. |
| matrix | Matrix | UN[`Matrix`](../../matrix) qui spécifie une transformation géométrique à appliquer au chemin. |
| warpMode | WarpMode | UN[`WarpMode`](../../warpmode) énumération qui spécifie si cette opération de déformation utilise le mode perspective ou bilinéaire. |
| flatness | Single | Une valeur comprise entre 0 et 1 qui spécifie à quel point le chemin résultant est plat. Pour plus d'informations, consultez le[`Flatten`](../flatten) méthodes. |

### Voir également

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* espace de noms [Aspose.Imaging](../../graphicspath)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

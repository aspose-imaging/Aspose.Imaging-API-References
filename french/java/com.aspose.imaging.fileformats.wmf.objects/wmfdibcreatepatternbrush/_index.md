---
title: "WmfDibCreatePatternBrush"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement META_DIBCREATEPATTERNBRUSH crée une section d'objet Brush 2.2.1.1 avec un motif spécifié par une section d'objet DeviceIndependentBitmap DIB 2.2.2.9."
type: docs
weight: 29
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfDibCreatePatternBrush extends WmfGraphicObject
```

L'enregistrement META\_DIBCREATEPATTERNBRUSH crée un objet Brush (section 2.2.1.1) avec un motif spécifié par un objet DeviceIndependentBitmap (DIB) (section 2.2.2.9).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfDibCreatePatternBrush()](#WmfDibCreatePatternBrush--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getStyle()](#getStyle--) | Obtient ou définit le style. |
| [setStyle(int value)](#setStyle-int-) | Obtient ou définit le style. |
| [getColorUsage()](#getColorUsage--) | Obtient ou définit l'utilisation de la couleur. |
| [setColorUsage(int value)](#setColorUsage-int-) | Obtient ou définit l'utilisation de la couleur. |
| [getSourceBitmap()](#getSourceBitmap--) | Obtient ou définit le bitmap source. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit le bitmap source. |
### WmfDibCreatePatternBrush() {#WmfDibCreatePatternBrush--}
```
public WmfDibCreatePatternBrush()
```


### getStyle() {#getStyle--}
```
public int getStyle()
```


Obtient ou définit le style.

Valeur : Les valeurs légales pour ce champ sont définies comme suit : si la valeur n'est pas BS\_PATTERN, BS\_DIBPATTERNPT DOIT être supposée. Ces valeurs sont spécifiées dans l'énumération BrushStyle (section 2.1.1.4).

**Returns:**
int
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Obtient ou définit le style.

Valeur : Les valeurs légales pour ce champ sont définies comme suit : si la valeur n'est pas BS\_PATTERN, BS\_DIBPATTERNPT DOIT être supposée. Ces valeurs sont spécifiées dans l'énumération BrushStyle (section 2.1.1.4).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Obtient ou définit l'utilisation de la couleur.

Valeur : Le champ Colors d'un objet DIB contient des valeurs RVB explicites, ou des index dans une palette.

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Obtient ou définit l'utilisation de la couleur.

Valeur : Le champ Colors d'un objet DIB contient des valeurs RVB explicites, ou des index dans une palette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Obtient ou définit le bitmap source.

Valeur : Données d'objet DIB à bits variables qui définissent le motif à utiliser dans le pinceau.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Obtient ou définit le bitmap source.

Valeur : Données d'objet DIB à bits variables qui définissent le motif à utiliser dans le pinceau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |


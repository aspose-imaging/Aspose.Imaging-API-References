---
title: "WmfCreatePatternBrush"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement META_CREATEPATTERNBRUSH crée un objet pinceau avec un motif spécifié par un bitmap."
type: docs
weight: 23
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePatternBrush extends WmfGraphicObject
```

L'enregistrement META\_CREATEPATTERNBRUSH crée un objet pinceau avec un motif spécifié par un bitmap.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfCreatePatternBrush()](#WmfCreatePatternBrush--) | WMFs l'enregistrement. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitmap()](#getBitmap--) | Obtient ou définit le bitmap. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Obtient ou définit le bitmap. |
| [getReserved()](#getReserved--) | Obtient ou définit le réservé. |
| [setReserved(byte[] value)](#setReserved-byte---) | Obtient ou définit le réservé. |
| [getPattern()](#getPattern--) | Obtient ou définit le motif. |
| [setPattern(byte[] value)](#setPattern-byte---) | Obtient ou définit le motif. |
### WmfCreatePatternBrush() {#WmfCreatePatternBrush--}
```
public WmfCreatePatternBrush()
```


WMFs l'enregistrement.

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Obtient ou définit le bitmap.

Valeur : Le bitmap qui spécifie le motif pour le pinceau.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Obtient ou définit le bitmap.

Valeur : Le bitmap qui spécifie le motif pour le pinceau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

### getReserved() {#getReserved--}
```
public byte[] getReserved()
```


Obtient ou définit le réservé.

Valeur : Réservé. Ce champ DOIT être ignoré.

**Returns:**
byte[]
### setReserved(byte[] value) {#setReserved-byte---}
```
public void setReserved(byte[] value)
```


Obtient ou définit le réservé.

Valeur : Réservé. Ce champ DOIT être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getPattern() {#getPattern--}
```
public byte[] getPattern()
```


Obtient ou définit le motif.

Valeur : Un tableau de bytes de longueur variable qui définit les données de pixels du bitmap composant le motif du pinceau. La longueur de ce champ, en bytes, peut être calculée à partir des paramètres du bitmap comme suit.

**Returns:**
byte[]
### setPattern(byte[] value) {#setPattern-byte---}
```
public void setPattern(byte[] value)
```


Obtient ou définit le motif.

Valeur : Un tableau de bytes de longueur variable qui définit les données de pixels du bitmap composant le motif du pinceau. La longueur de ce champ, en bytes, peut être calculée à partir des paramètres du bitmap comme suit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |


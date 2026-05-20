---
title: "EmfPlusBitmapData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusBitmapData spécifie une image bitmap avec des données de pixels."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusBitmapData extends EmfPlusBaseBitmapData
```

L'objet EmfPlusBitmapData spécifie une image bitmap avec des données de pixels.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColors()](#getColors--) | Obtient ou définit les couleurs de la palette Colors (variable) : un objet optionnel `EmfPlusPalette` (section 2.2.2.28), qui spécifie la palette de couleurs utilisée dans les données de pixels. |
| [setColors(EmfPlusPalette value)](#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Obtient ou définit les couleurs de la palette Colors (variable) : un objet optionnel `EmfPlusPalette` (section 2.2.2.28), qui spécifie la palette de couleurs utilisée dans les données de pixels. |
| [getPixelData()](#getPixelData--) | Obtient ou définit les données de pixel PixelData (variable) : un tableau d'octets qui spécifient les données de pixel. |
| [setPixelData(byte[] value)](#setPixelData-byte---) | Obtient ou définit les données de pixel PixelData (variable) : un tableau d'octets qui spécifient les données de pixel. |
### EmfPlusBitmapData() {#EmfPlusBitmapData--}
```
public EmfPlusBitmapData()
```


### getColors() {#getColors--}
```
public EmfPlusPalette getColors()
```


Obtient ou définit les couleurs de la palette Colors (variable) : un objet optionnel `EmfPlusPalette` (section 2.2.2.28), qui spécifie la palette de couleurs utilisée dans les données de pixels. Ce champ DOIT être présent si le drapeau I est défini dans le champ PixelFormat de l'objet `EmfPlusBitmap`.

Valeur : Les couleurs.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setColors(EmfPlusPalette value) {#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setColors(EmfPlusPalette value)
```


Obtient ou définit les couleurs de la palette Colors (variable) : un objet optionnel `EmfPlusPalette` (section 2.2.2.28), qui spécifie la palette de couleurs utilisée dans les données de pixels. Ce champ DOIT être présent si le drapeau I est défini dans le champ PixelFormat de l'objet `EmfPlusBitmap`.

Valeur : Les couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

### getPixelData() {#getPixelData--}
```
public byte[] getPixelData()
```


Obtient ou définit les données de pixel PixelData (variable) : un tableau d'octets qui spécifient les données de pixel. La taille et le format de ces données peuvent être calculés à partir des champs de l'objet EmfPlusBitmap, y compris le format de pixel provenant de l'énumération `Consts.EmfPlusPixelFormat` (section 2.1.1.25).

Valeur : les données de pixel.

**Returns:**
byte[]
### setPixelData(byte[] value) {#setPixelData-byte---}
```
public void setPixelData(byte[] value)
```


Obtient ou définit les données de pixel PixelData (variable) : un tableau d'octets qui spécifient les données de pixel. La taille et le format de ces données peuvent être calculés à partir des champs de l'objet EmfPlusBitmap, y compris le format de pixel provenant de l'énumération `Consts.EmfPlusPixelFormat` (section 2.1.1.25).

Valeur : les données de pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |


---
title: "DxfOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'API pour la création d'images vectorielles au format Drawing Interchange Format DXF offre des solutions sur mesure pour générer des fichiers de dessin AutoCAD avec précision et flexibilité."
type: docs
weight: 17
url: /fr/java/com.aspose.imaging.imageoptions/dxfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DxfOptions extends ImageOptionsBase
```

L'API pour la création d'images vectorielles au format Drawing Interchange Format (DXF) offre des solutions sur mesure pour générer des fichiers de dessin AutoCAD avec précision et flexibilité. Conçue spécifiquement pour travailler avec des lignes de texte et des courbes de Bézier, les développeurs peuvent manipuler efficacement ces éléments, compter les points de Bézier et convertir les courbes en polylignes pour une exportation fluide, garantissant la compatibilité et la fidélité des images vectorielles DXF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DxfOptions()](#DxfOptions--) |  |
| [DxfOptions(DxfOptions imageOptions)](#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-) | Constructeur de Coping |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBezierPointCount()](#getBezierPointCount--) | Nombre de points à générer lors de la conversion des courbes de Bézier en polylignes, minimum 4. |
| [setBezierPointCount(byte value)](#setBezierPointCount-byte-) | Nombre de points à générer lors de la conversion des courbes de Bézier en polylignes, minimum 4. |
| [getConvertTextBeziers()](#getConvertTextBeziers--) | Fonctionne lorsque \#textAsLines est défini sur `true`. |
| [setConvertTextBeziers(boolean value)](#setConvertTextBeziers-boolean-) | Fonctionne lorsque \#textAsLines est défini sur `true`. |
| [getTextAsLines()](#getTextAsLines--) | Indique si le texte doit être exporté sous forme de contours composés de polylignes (par défaut) ou sous forme d'entités TEXT éditables d'Autocad. |
| [setTextAsLines(boolean value)](#setTextAsLines-boolean-) | Indique si le texte doit être exporté sous forme de contours composés de polylignes (par défaut) ou sous forme d'entités TEXT éditables d'Autocad. |

## Example: This example demonstrates export to Dxf format

``` java

//Créez une instance Image et initialisez‑la avec un fichier image existant depuis l'emplacement du disque
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("input.svg"))
{
    com.aspose.imaging.imageoptions.DxfOptions options = new com.aspose.imaging.imageoptions.DxfOptions();
    options.setTextAsLines(true);
    options.setConvertTextBeziers(true);
    options.setBezierPointCount((byte)20);
    image.save("output.dxf", options);
}
```

### DxfOptions() {#DxfOptions--}
```
public DxfOptions()
```


### DxfOptions(DxfOptions imageOptions) {#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-}
```
public DxfOptions(DxfOptions imageOptions)
```


Constructeur de Coping

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageOptions | [DxfOptions](../../com.aspose.imaging.imageoptions/dxfoptions) | Les options source pour Coping |

### getBezierPointCount() {#getBezierPointCount--}
```
public final byte getBezierPointCount()
```


Nombre de points à générer lors de la conversion des courbes de Bézier en polylignes, minimum 4. Utilisé lorsque (/) et (/) sont tous deux /// définis sur `true`

**Returns:**
byte
### setBezierPointCount(byte value) {#setBezierPointCount-byte-}
```
public final void setBezierPointCount(byte value)
```


Nombre de points à générer lors de la conversion des courbes de Bézier en polylignes, minimum 4. Utilisé lorsque (/) et (/) sont tous deux /// définis sur `true`

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getConvertTextBeziers() {#getConvertTextBeziers--}
```
public final boolean getConvertTextBeziers()
```


Fonctionne lorsque \#textAsLines est défini sur `true`. Indique s'il faut convertir les courbes de Bézier dans les contours de texte en polylignes multipoints.

**Returns:**
boolean
### setConvertTextBeziers(boolean value) {#setConvertTextBeziers-boolean-}
```
public final void setConvertTextBeziers(boolean value)
```


Fonctionne lorsque \#textAsLines est défini sur `true`. Indique s'il faut convertir les courbes de Bézier dans les contours de texte en polylignes multipoints.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getTextAsLines() {#getTextAsLines--}
```
public final boolean getTextAsLines()
```


Indique si le texte doit être exporté sous forme de contours composés de polylignes (par défaut) ou sous forme d'entités TEXT éditables d'Autocad. Si cette option est définie

**Returns:**
boolean
### setTextAsLines(boolean value) {#setTextAsLines-boolean-}
```
public final void setTextAsLines(boolean value)
```


Indique si le texte doit être exporté sous forme de contours composés de polylignes (par défaut) ou sous forme d'entités TEXT éditables d'Autocad. Si cette option est définie

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |


---
title: "Time"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représentation d'une valeur temporelle en secondes."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.xmp.schemas.xmpdm/time/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Représentation d'une valeur temporelle en secondes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.imaging.xmp.types.derived.Rational-int-) | Initialise une nouvelle instance de la classe `Time`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getScale()](#getScale--) | Obtient ou définit l'échelle de la valeur temporelle. |
| [setScale(Rational value)](#setScale-com.aspose.imaging.xmp.types.derived.Rational-) | Obtient ou définit l'échelle de la valeur temporelle. |
| [getValue()](#getValue--) | Obtient ou définit la valeur temporelle dans l'échelle spécifiée. |
| [setValue(int value)](#setValue-int-) | Obtient ou définit la valeur temporelle dans l'échelle spécifiée. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtient la valeur de chaîne contenue au format XMP. |
### Time(Rational scale, int value) {#Time-com.aspose.imaging.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Initialise une nouvelle instance de la classe `Time`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) | L'échelle. |
| valeur | int | La valeur. |

### getScale() {#getScale--}
```
public Rational getScale()
```


Obtient ou définit l'échelle de la valeur temporelle.

Pour NTSC, utilisez 1001/30000, ou le moins précis 100/2997. Pour PAL, utilisez 1/25. Valeur : L'échelle pour la valeur temporelle.

**Returns:**
[Rational](../../com.aspose.imaging.xmp.types.derived/rational)
### setScale(Rational value) {#setScale-com.aspose.imaging.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Obtient ou définit l'échelle de la valeur temporelle.

Pour NTSC, utilisez 1001/30000, ou le moins précis 100/2997. Pour PAL, utilisez 1/25. Valeur : L'échelle pour la valeur temporelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) |  |

### getValue() {#getValue--}
```
public int getValue()
```


Obtient ou définit la valeur temporelle dans l'échelle spécifiée.

Valeur : La valeur temporelle dans l'échelle spécifiée.

**Returns:**
int
### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Obtient ou définit la valeur temporelle dans l'échelle spécifiée.

Valeur : La valeur temporelle dans l'échelle spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Obtient la valeur de chaîne contenue au format XMP.

**Returns:**
java.lang.String - Retourne la valeur de chaîne contenue au format XMP.

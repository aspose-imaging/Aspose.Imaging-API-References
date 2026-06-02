---
title: "Os22XBitmapHeader"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Un OS/2 2.x OS22XBITMAPHEADER également appelé BITMAPCOREHEADER2."
type: docs
weight: 16
url: /fr/java/com.aspose.imaging.fileformats.bmp/os22xbitmapheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class Os22XBitmapHeader extends BitmapInfoHeader
```

Un OS/2 2.x OS22XBITMAPHEADER également appelé BITMAPCOREHEADER2.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getUnits()](#getUnits--) | Obtient les unités. |
| [getReserved()](#getReserved--) | Obtient la valeur réservée. |
| [getRecording()](#getRecording--) | Obtient l'enregistrement. |
| [getRendering()](#getRendering--) | Obtient le rendu. |
| [getSize1()](#getSize1--) | Obtient la taille1. |
| [getSize2()](#getSize2--) | Obtient la taille2. |
| [getColorEncoding()](#getColorEncoding--) | Obtient le codage couleur. |
| [getIdentifier()](#getIdentifier--) | Obtient l'identifiant. |
### getUnits() {#getUnits--}
```
public int getUnits()
```


Obtient les unités.

**Returns:**
int - Type d'unités utilisées pour mesurer la résolution
### getReserved() {#getReserved--}
```
public int getReserved()
```


Obtient la valeur réservée.

**Returns:**
int - Remplir la structure à la frontière de 4 octets
### getRecording() {#getRecording--}
```
public int getRecording()
```


Obtient l'enregistrement.

**Returns:**
int - Algorithme d'enregistrement
### getRendering() {#getRendering--}
```
public int getRendering()
```


Obtient le rendu.

**Returns:**
int - Algorithme de demi-teinte utilisé
### getSize1() {#getSize1--}
```
public int getSize1()
```


Obtient la taille1.

**Returns:**
int - Réservé à l'utilisation de l'algorithme de demi-teinte
### getSize2() {#getSize2--}
```
public int getSize2()
```


Obtient la taille2.

**Returns:**
int - Réservé à l'utilisation de l'algorithme de demi-teinte
### getColorEncoding() {#getColorEncoding--}
```
public int getColorEncoding()
```


Obtient le codage couleur.

**Returns:**
int - Modèle de couleur utilisé dans le bitmap
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Obtient l'identifiant.

**Returns:**
int - Réservé à l'usage de l'application

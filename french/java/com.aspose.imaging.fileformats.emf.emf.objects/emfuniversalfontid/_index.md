---
title: "EmfUniversalFontId"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet UniversalFontId définit un mécanisme d'identification des polices dans les métafichiers EMF."
type: docs
weight: 37
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfUniversalFontId extends EmfObject
```

L'objet UniversalFontId définit un mécanisme d'identification des polices dans les métafichiers EMF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfUniversalFontId()](#EmfUniversalFontId--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getChecksum()](#getChecksum--) | Obtient ou définit un entier non signé de 32 bits qui est la somme de contrôle de la police. |
| [setChecksum(int value)](#setChecksum-int-) | Obtient ou définit un entier non signé de 32 bits qui est la somme de contrôle de la police. |
| [getIndex()](#getIndex--) | Obtient ou définit un entier non signé de 32 bits qui est un indice associé à l'objet police. |
| [setIndex(int value)](#setIndex-int-) | Obtient ou définit un entier non signé de 32 bits qui est un indice associé à l'objet police. |
### EmfUniversalFontId() {#EmfUniversalFontId--}
```
public EmfUniversalFontId()
```


### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Obtient ou définit un entier non signé de 32 bits qui est la somme de contrôle de la police. La valeur de la somme de contrôle a les significations suivantes. 0x00000000 L'objet est une police de dispositif. 0x00000001 L'objet est une police Type 1 qui a été installée sur la machine cliente et est répertoriée par le pilote d'imprimante PostScript comme une police de dispositif. 0x00000002 L'objet n'est pas une police mais un rasteriseur Type 1. 3 \\u2264 valeur L'objet est une police bitmap, vectorielle ou TrueType, ou une police rasterisée Type 1 qui a été créée par un rasteriseur Type 1.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Obtient ou définit un entier non signé de 32 bits qui est la somme de contrôle de la police. La valeur de la somme de contrôle a les significations suivantes. 0x00000000 L'objet est une police de dispositif. 0x00000001 L'objet est une police Type 1 qui a été installée sur la machine cliente et est répertoriée par le pilote d'imprimante PostScript comme une police de dispositif. 0x00000002 L'objet n'est pas une police mais un rasteriseur Type 1. 3 \\u2264 valeur L'objet est une police bitmap, vectorielle ou TrueType, ou une police rasterisée Type 1 qui a été créée par un rasteriseur Type 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getIndex() {#getIndex--}
```
public int getIndex()
```


Obtient ou définit un entier non signé de 32 bits qui est un indice associé à l'objet police. La signification de ce champ est déterminée par le type de police.

**Returns:**
int
### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Obtient ou définit un entier non signé de 32 bits qui est un indice associé à l'objet police. La signification de ce champ est déterminée par le type de police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |


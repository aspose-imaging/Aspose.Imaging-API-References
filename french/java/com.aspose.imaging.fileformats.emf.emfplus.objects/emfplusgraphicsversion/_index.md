---
title: "EmfPlusGraphicsVersion"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusGraphicsVersion spécifie la version des graphiques du système d'exploitation utilisée pour créer un métafichier EMF."
type: docs
weight: 44
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusGraphicsVersion extends EmfPlusStructureObjectType
```

L'objet EmfPlusGraphicsVersion spécifie la version des graphiques du système d'exploitation utilisée pour créer un métafichier EMF+.

Les versions graphiques sont extensibles par le fournisseur ; cependant, pour garantir l'interopérabilité, toute extension de ce type DOIT être implémentée à la fois dans les clients et les serveurs des métafichiers EMF+.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusGraphicsVersion()](#EmfPlusGraphicsVersion--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMetafileSignature()](#getMetafileSignature--) | Obtient une MetafileSignature (20 bits) : une valeur qui identifie le type de métafichier. |
| [setMetafileSignature(int value)](#setMetafileSignature-int-) | Obtient une MetafileSignature (20 bits) : une valeur qui identifie le type de métafichier. |
| [getGraphicsVersion()](#getGraphicsVersion--) | Obtient une GraphicsVersion (12 bits) : la version des graphiques du système d'exploitation. |
| [setGraphicsVersion(int value)](#setGraphicsVersion-int-) | Obtient une GraphicsVersion (12 bits) : la version des graphiques du système d'exploitation. |
### EmfPlusGraphicsVersion() {#EmfPlusGraphicsVersion--}
```
public EmfPlusGraphicsVersion()
```


### getMetafileSignature() {#getMetafileSignature--}
```
public int getMetafileSignature()
```


Obtient une MetafileSignature (20 bits) : une valeur qui identifie le type de métafichier. La valeur pour un métafichier EMF+ est 0xDBC01.

**Returns:**
int
### setMetafileSignature(int value) {#setMetafileSignature-int-}
```
public void setMetafileSignature(int value)
```


Obtient une MetafileSignature (20 bits) : une valeur qui identifie le type de métafichier. La valeur pour un métafichier EMF+ est 0xDBC01.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getGraphicsVersion() {#getGraphicsVersion--}
```
public int getGraphicsVersion()
```


Obtient une GraphicsVersion (12 bits) : la version des graphiques du système d'exploitation. Cette valeur DOIT être définie dans l'énumération `EmfPlusGraphicsVersion`

**Returns:**
int
### setGraphicsVersion(int value) {#setGraphicsVersion-int-}
```
public void setGraphicsVersion(int value)
```


Obtient une GraphicsVersion (12 bits) : la version des graphiques du système d'exploitation. Cette valeur DOIT être définie dans l'énumération `EmfPlusGraphicsVersion`

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |


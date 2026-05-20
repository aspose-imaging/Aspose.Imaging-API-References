---
title: "EmfPlusImageAttributes"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusImageAttributes spécifie comment les couleurs d'image bitmap sont manipulées lors du rendu."
type: docs
weight: 48
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImageAttributes extends EmfPlusGraphicsObjectType
```

L'objet EmfPlusImageAttributes spécifie comment les couleurs d'image bitmap sont manipulées lors du rendu.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment gérer les conditions de bord avec une valeur de l'énumération WrapMode (section 2.1.1.34). |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment gérer les conditions de bord avec une valeur de l'énumération WrapMode (section 2.1.1.34). |
| [getClampArgb32Color()](#getClampArgb32Color--) | Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur de bord à utiliser lorsque la valeur WrapMode est WrapModeClamp. |
| [setClampArgb32Color(int value)](#setClampArgb32Color-int-) | Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur de bord à utiliser lorsque la valeur WrapMode est WrapModeClamp. |
| [getObjectClamp()](#getObjectClamp--) | Obtient ou définit un entier signé de 32 bits qui spécifie le comportement de serrage de l'objet. |
| [setObjectClamp(int value)](#setObjectClamp-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le comportement de serrage de l'objet. |
### EmfPlusImageAttributes() {#EmfPlusImageAttributes--}
```
public EmfPlusImageAttributes()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment gérer les conditions de bord avec une valeur de l'énumération WrapMode (section 2.1.1.34).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment gérer les conditions de bord avec une valeur de l'énumération WrapMode (section 2.1.1.34).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getClampArgb32Color() {#getClampArgb32Color--}
```
public int getClampArgb32Color()
```


Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur de bord à utiliser lorsque la valeur WrapMode est WrapModeClamp. Cette couleur est visible lorsque le rectangle source traité par un enregistrement EmfPlusDrawImage (section 2.3.4.8) est plus grand que l'image elle‑même.

**Returns:**
int
### setClampArgb32Color(int value) {#setClampArgb32Color-int-}
```
public void setClampArgb32Color(int value)
```


Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur de bord à utiliser lorsque la valeur WrapMode est WrapModeClamp. Cette couleur est visible lorsque le rectangle source traité par un enregistrement EmfPlusDrawImage (section 2.3.4.8) est plus grand que l'image elle‑même.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getObjectClamp() {#getObjectClamp--}
```
public int getObjectClamp()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le comportement de serrage de l'objet. Il n'est pas utilisé tant que cet objet n'est pas appliqué à une image en cours de rendu. Cette valeur DOIT être l'une des valeurs définies dans le tableau suivant.

**Returns:**
int
### setObjectClamp(int value) {#setObjectClamp-int-}
```
public void setObjectClamp(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le comportement de serrage de l'objet. Il n'est pas utilisé tant que cet objet n'est pas appliqué à une image en cours de rendu. Cette valeur DOIT être l'une des valeurs définies dans le tableau suivant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |


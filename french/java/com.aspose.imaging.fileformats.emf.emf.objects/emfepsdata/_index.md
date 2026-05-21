---
title: "EmfEpsData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EpsData est un conteneur pour les données EPS."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfEpsData extends EmfObject
```

L'objet EpsData est un conteneur pour les données EPS.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfEpsData()](#EmfEpsData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSizeData()](#getSizeData--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille totale de cet objet, en octets |
| [setSizeData(int value)](#setSizeData-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille totale de cet objet, en octets |
| [getVersion()](#getVersion--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le niveau du langage PostScript. |
| [setVersion(int value)](#setVersion-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le niveau du langage PostScript. |
| [getPoints()](#getPoints--) | Obtient ou définit un tableau de trois objets Point28\_4 (section 2.2.23) qui définit les coordonnées du parallélogramme de sortie en utilisant la notation FIX de 28,4 bits |
| [setPoints(EmfPoint28To4[] value)](#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---) | Obtient ou définit un tableau de trois objets Point28\_4 (section 2.2.23) qui définit les coordonnées du parallélogramme de sortie en utilisant la notation FIX de 28,4 bits |
| [getPostScriptData()](#getPostScriptData--) | Obtient ou définit un tableau d'octets de données PostScript. |
| [setPostScriptData(byte[] value)](#setPostScriptData-byte---) | Obtient ou définit un tableau d'octets de données PostScript. |
### EmfEpsData() {#EmfEpsData--}
```
public EmfEpsData()
```


### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille totale de cet objet, en octets

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille totale de cet objet, en octets

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le niveau du langage PostScript. Cette valeur DOIT être 0x00000001

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le niveau du langage PostScript. Cette valeur DOIT être 0x00000001

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPoints() {#getPoints--}
```
public EmfPoint28To4[] getPoints()
```


Obtient ou définit un tableau de trois objets Point28\_4 (section 2.2.23) qui définit les coordonnées du parallélogramme de sortie en utilisant la notation FIX de 28,4 bits

Le coin supérieur gauche du parallélogramme est le premier point de ce tableau, le coin supérieur droit est le deuxième point, et le coin inférieur gauche est le troisième point. Le coin inférieur droit du parallélogramme est calculé à partir des trois premiers points (A, B et C) en les traitant comme des vecteurs.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4[]
### setPoints(EmfPoint28To4[] value) {#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---}
```
public void setPoints(EmfPoint28To4[] value)
```


Obtient ou définit un tableau de trois objets Point28\_4 (section 2.2.23) qui définit les coordonnées du parallélogramme de sortie en utilisant la notation FIX de 28,4 bits

Le coin supérieur gauche du parallélogramme est le premier point de ce tableau, le coin supérieur droit est le deuxième point, et le coin inférieur gauche est le troisième point. Le coin inférieur droit du parallélogramme est calculé à partir des trois premiers points (A, B et C) en les traitant comme des vecteurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPoint28To4\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4) |  |

### getPostScriptData() {#getPostScriptData--}
```
public byte[] getPostScriptData()
```


Obtient ou définit un tableau d'octets de données PostScript. La longueur de ce tableau peut être calculée à partir du champ SizeData. Ces données PEUVENT être utilisées pour rendre une image.

**Returns:**
byte[]
### setPostScriptData(byte[] value) {#setPostScriptData-byte---}
```
public void setPostScriptData(byte[] value)
```


Obtient ou définit un tableau d'octets de données PostScript. La longueur de ce tableau peut être calculée à partir du champ SizeData. Ces données PEUVENT être utilisées pour rendre une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |


---
title: "EmfPlusImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusImage spécifie une image graphique sous forme de bitmap ou de métafichier."
type: docs
weight: 47
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImage extends EmfPlusGraphicsObjectType
```

L'objet EmfPlusImage spécifie une image graphique sous forme de bitmap ou de métafichier.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusImage()](#EmfPlusImage--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getImageData()](#getImageData--) | Obtient ou définit les données d'image de longueur variable qui définissent les données d'image spécifiées dans le champ Type. |
| [setImageData(EmfPlusBaseImageData value)](#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-) | Obtient ou définit les données d'image de longueur variable qui définissent les données d'image spécifiées dans le champ Type. |
| [getType()](#getType--) | Obtient ou définit le type d'image, un entier non signé de 32 bits qui spécifie le type de données dans le champ ImageData. |
| [setType(int value)](#setType-int-) | Obtient ou définit le type d'image, un entier non signé de 32 bits qui spécifie le type de données dans le champ ImageData. |
### EmfPlusImage() {#EmfPlusImage--}
```
public EmfPlusImage()
```


### getImageData() {#getImageData--}
```
public EmfPlusBaseImageData getImageData()
```


Obtient ou définit les données d'image de longueur variable qui définissent les données d'image spécifiées dans le champ Type. Le contenu et le format des données peuvent varier selon chaque type d'image.

**Returns:**
[EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
### setImageData(EmfPlusBaseImageData value) {#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-}
```
public void setImageData(EmfPlusBaseImageData value)
```


Obtient ou définit les données d'image de longueur variable qui définissent les données d'image spécifiées dans le champ Type. Le contenu et le format des données peuvent varier selon chaque type d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata) |  |

### getType() {#getType--}
```
public int getType()
```


Obtient ou définit le type d'image, un entier non signé de 32 bits qui spécifie le type de données dans le champ ImageData. Cette valeur DOIT être définie dans l'énumération ImageDataType (section 2.1.1.15).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Obtient ou définit le type d'image, un entier non signé de 32 bits qui spécifie le type de données dans le champ ImageData. Cette valeur DOIT être définie dans l'énumération ImageDataType (section 2.1.1.15).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |


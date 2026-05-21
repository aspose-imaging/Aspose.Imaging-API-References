---
title: "EmfHeaderExtension1"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet HeaderExtension1 définit la première extension de l'en-tête du métafichier EMF."
type: docs
weight: 18
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
```
public final class EmfHeaderExtension1 extends EmfHeaderObject
```

L'objet HeaderExtension1 définit la première extension de l'en-tête du métafichier EMF. Il ajoute la prise en charge d'un objet PixelFormatDescriptor (section 2.2.22) et des enregistrements OpenGL [OPENGL] (section 2.3.9).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCbPixelFormat()](#getCbPixelFormat--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille de l'objet PixelFormatDescriptor. |
| [setCbPixelFormat(int value)](#setCbPixelFormat-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille de l'objet PixelFormatDescriptor. |
| [getOffPixelFormat()](#getOffPixelFormat--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage vers l'objet PixelFormatDescriptor. |
| [setOffPixelFormat(int value)](#setOffPixelFormat-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage vers l'objet PixelFormatDescriptor. |
| [getBOpenGl()](#getBOpenGl--) | Obtient ou définit un entier non signé de 32 bits qui indique si des commandes OpenGL sont présentes dans le métafichier. |
| [setBOpenGl(int value)](#setBOpenGl-int-) | Obtient ou définit un entier non signé de 32 bits qui indique si des commandes OpenGL sont présentes dans le métafichier. |
### EmfHeaderExtension1() {#EmfHeaderExtension1--}
```
public EmfHeaderExtension1()
```


### getCbPixelFormat() {#getCbPixelFormat--}
```
public int getCbPixelFormat()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille de l'objet PixelFormatDescriptor. Cette valeur DOIT être 0x00000000 si aucun format de pixel n'est défini.

**Returns:**
int
### setCbPixelFormat(int value) {#setCbPixelFormat-int-}
```
public void setCbPixelFormat(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille de l'objet PixelFormatDescriptor. Cette valeur DOIT être 0x00000000 si aucun format de pixel n'est défini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getOffPixelFormat() {#getOffPixelFormat--}
```
public int getOffPixelFormat()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage vers l'objet PixelFormatDescriptor. Cette valeur DOIT être 0x00000000 si aucun format de pixel n'est défini.

**Returns:**
int
### setOffPixelFormat(int value) {#setOffPixelFormat-int-}
```
public void setOffPixelFormat(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage vers l'objet PixelFormatDescriptor. Cette valeur DOIT être 0x00000000 si aucun format de pixel n'est défini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBOpenGl() {#getBOpenGl--}
```
public int getBOpenGl()
```


Obtient ou définit un entier non signé de 32 bits qui indique si des commandes OpenGL sont présentes dans le métafichier. 0x00000000 Les enregistrements OpenGL ne sont pas présents dans le métafichier. 0x00000001 Les enregistrements OpenGL sont présents dans le métafichier.

**Returns:**
int
### setBOpenGl(int value) {#setBOpenGl-int-}
```
public void setBOpenGl(int value)
```


Obtient ou définit un entier non signé de 32 bits qui indique si des commandes OpenGL sont présentes dans le métafichier. 0x00000000 Les enregistrements OpenGL ne sont pas présents dans le métafichier. 0x00000001 Les enregistrements OpenGL sont présents dans le métafichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |


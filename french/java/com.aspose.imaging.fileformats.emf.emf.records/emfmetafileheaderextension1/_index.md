---
title: "EmfMetafileHeaderExtension1"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfMetafileHeaderExtension1 est l'enregistrement d'en-tête utilisé dans la première extension des métafichiers EMF."
type: docs
weight: 71
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
```
public class EmfMetafileHeaderExtension1 extends EmfMetafileHeader
```

L'enregistrement EmfMetafileHeaderExtension1 est l'enregistrement d'en-tête utilisé dans la première extension des métafichiers EMF. Après le champ EmfHeaderExtension1, les champs restants sont optionnels et peuvent être présents dans n'importe quel ordre.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfMetafileHeaderExtension1(EmfMetafileHeader header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Initialise une nouvelle instance de la classe `EmfMetafileHeaderExtension1`. |
| [EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-) | Initialise une nouvelle instance de la classe `EmfMetafileHeaderExtension1`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEmfHeaderExtension1()](#getEmfHeaderExtension1--) | Obtient ou définit un objet HeaderExtension1, qui spécifie des informations supplémentaires sur l'image dans le métafichier. |
| [setEmfHeaderExtension1(EmfHeaderExtension1 value)](#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-) | Obtient ou définit un objet HeaderExtension1, qui spécifie des informations supplémentaires sur l'image dans le métafichier. |
| [getEmfPixelFormatBuffer()](#getEmfPixelFormatBuffer--) | Obtient ou définit un tableau d'octets optionnel qui contient le descripteur de format de pixel EMF, qui n'est pas tenu d'être contigu avec la partie fixe de l'enregistrement EmfMetafileHeaderExtension1 ou avec la chaîne de description EMF. |
| [setEmfPixelFormatBuffer(byte[] value)](#setEmfPixelFormatBuffer-byte---) | Obtient ou définit un tableau d'octets optionnel qui contient le descripteur de format de pixel EMF, qui n'est pas tenu d'être contigu avec la partie fixe de l'enregistrement EmfMetafileHeaderExtension1 ou avec la chaîne de description EMF. |
### EmfMetafileHeaderExtension1(EmfMetafileHeader header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeader header)
```


Initialise une nouvelle instance de la classe `EmfMetafileHeaderExtension1`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | L'en-tête. |

### EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)
```


Initialise une nouvelle instance de la classe `EmfMetafileHeaderExtension1`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| header | [EmfMetafileHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) | L'en-tête. |

### getEmfHeaderExtension1() {#getEmfHeaderExtension1--}
```
public EmfHeaderExtension1 getEmfHeaderExtension1()
```


Obtient ou définit un objet HeaderExtension1, qui spécifie des informations supplémentaires sur l'image dans le métafichier.

**Returns:**
[EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1)
### setEmfHeaderExtension1(EmfHeaderExtension1 value) {#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-}
```
public void setEmfHeaderExtension1(EmfHeaderExtension1 value)
```


Obtient ou définit un objet HeaderExtension1, qui spécifie des informations supplémentaires sur l'image dans le métafichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1) |  |

### getEmfPixelFormatBuffer() {#getEmfPixelFormatBuffer--}
```
public byte[] getEmfPixelFormatBuffer()
```


Obtient ou définit un tableau d'octets optionnel qui contient le descripteur de format de pixel EMF, qui n'est pas tenu d'être contigu avec la partie fixe de l'enregistrement EmfMetafileHeaderExtension1 ou avec la chaîne de description EMF. En conséquence, le champ de ce tampon intitulé "UndefinedSpace" est optionnel et DOIT être ignoré.

**Returns:**
byte[]
### setEmfPixelFormatBuffer(byte[] value) {#setEmfPixelFormatBuffer-byte---}
```
public void setEmfPixelFormatBuffer(byte[] value)
```


Obtient ou définit un tableau d'octets optionnel qui contient le descripteur de format de pixel EMF, qui n'est pas tenu d'être contigu avec la partie fixe de l'enregistrement EmfMetafileHeaderExtension1 ou avec la chaîne de description EMF. En conséquence, le champ de ce tampon intitulé "UndefinedSpace" est optionnel et DOIT être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |


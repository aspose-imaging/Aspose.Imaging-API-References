---
title: "EmfHeaderObject"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet Header définit l'en-tête du métafichier EMF."
type: docs
weight: 20
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfHeaderObject extends EmfObject
```

L'objet Header définit l'en-tête du métafichier EMF. Il spécifie les propriétés du dispositif sur lequel l'image du métafichier a été créée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfHeaderObject()](#EmfHeaderObject--) | Initialise une nouvelle instance de la classe `EmfHeaderObject`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie les limites rectangulaires inclusives-inclusives en unités du dispositif du plus petit rectangle pouvant être tracé autour de l'image stockée dans le métafichier |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie les limites rectangulaires inclusives-inclusives en unités du dispositif du plus petit rectangle pouvant être tracé autour de l'image stockée dans le métafichier |
| [getFrame()](#getFrame--) | Obtient ou définit un objet WMF RectL qui spécifie les dimensions rectangulaires inclusives-inclusives, en unités de 0,01 millimètre, d'un rectangle entourant l'image stockée dans le métafichier |
| [setFrame(Rectangle value)](#setFrame-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL qui spécifie les dimensions rectangulaires inclusives-inclusives, en unités de 0,01 millimètre, d'un rectangle entourant l'image stockée dans le métafichier |
| [getRecordSignature()](#getRecordSignature--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la signature de l'enregistrement. |
| [setRecordSignature(int value)](#setRecordSignature-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la signature de l'enregistrement. |
| [getVersion()](#getVersion--) | Obtient ou définit Version (4 octets) : un entier non signé de 32 bits qui spécifie l'interopérabilité du métafichier EMF. |
| [setVersion(int value)](#setVersion-int-) | Obtient ou définit Version (4 octets) : un entier non signé de 32 bits qui spécifie l'interopérabilité du métafichier EMF. |
| [getBytes()](#getBytes--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille du métafichier, en octets. |
| [setBytes(int value)](#setBytes-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille du métafichier, en octets. |
| [getRecords()](#getRecords--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'enregistrements dans le métafichier |
| [setRecords(int value)](#setRecords-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'enregistrements dans le métafichier |
| [getHandles()](#getHandles--) | Obtient ou définit un entier non signé de 16 bits qui spécifie le nombre d'objets graphiques qui seront utilisés lors du traitement du métafichier |
| [setHandles(short value)](#setHandles-short-) | Obtient ou définit un entier non signé de 16 bits qui spécifie le nombre d'objets graphiques qui seront utilisés lors du traitement du métafichier |
| [getReserved()](#getReserved--) | Obtient ou définit un entier non signé de 16 bits qui DOIT être 0x0000 et DOIT être ignoré |
| [setReserved(short value)](#setReserved-short-) | Obtient ou définit un entier non signé de 16 bits qui DOIT être 0x0000 et DOIT être ignoré |
| [getNDesription()](#getNDesription--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de caractères dans le tableau contenant la description du contenu du métafichier. |
| [setNDesription(int value)](#setNDesription-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de caractères dans le tableau contenant la description du contenu du métafichier. |
| [getOffDescription()](#getOffDescription--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage depuis le début de cet enregistrement jusqu'au tableau contenant la description du contenu du métafichier |
| [setOffDescription(int value)](#setOffDescription-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage depuis le début de cet enregistrement jusqu'au tableau contenant la description du contenu du métafichier |
| [getNPalEntries()](#getNPalEntries--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'entrées dans la palette du métafichier. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'entrées dans la palette du métafichier. |
| [getDevice()](#getDevice--) | Obtient ou définit un objet WMF SizeL ([MS-WMF] section 2.2.2.22) qui spécifie la taille du dispositif de référence, en pixels |
| [setDevice(Size value)](#setDevice-com.aspose.imaging.Size-) | Obtient ou définit un objet WMF SizeL ([MS-WMF] section 2.2.2.22) qui spécifie la taille du dispositif de référence, en pixels |
| [getMillimeters()](#getMillimeters--) | Obtient ou définit un objet WMF SizeL qui spécifie la taille du dispositif de référence, en millimètres |
| [setMillimeters(Size value)](#setMillimeters-com.aspose.imaging.Size-) | Obtient ou définit un objet WMF SizeL qui spécifie la taille du dispositif de référence, en millimètres |
| [getValid()](#getValid--) | Obtient une valeur indiquant si cet `EmfHeaderObject` est valide. |
### EmfHeaderObject() {#EmfHeaderObject--}
```
public EmfHeaderObject()
```


Initialise une nouvelle instance de la classe `EmfHeaderObject`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie les limites rectangulaires inclusives-inclusives en unités du dispositif du plus petit rectangle pouvant être tracé autour de l'image stockée dans le métafichier

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie les limites rectangulaires inclusives-inclusives en unités du dispositif du plus petit rectangle pouvant être tracé autour de l'image stockée dans le métafichier

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getFrame() {#getFrame--}
```
public Rectangle getFrame()
```


Obtient ou définit un objet WMF RectL qui spécifie les dimensions rectangulaires inclusives-inclusives, en unités de 0,01 millimètre, d'un rectangle entourant l'image stockée dans le métafichier

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setFrame(Rectangle value) {#setFrame-com.aspose.imaging.Rectangle-}
```
public void setFrame(Rectangle value)
```


Obtient ou définit un objet WMF RectL qui spécifie les dimensions rectangulaires inclusives-inclusives, en unités de 0,01 millimètre, d'un rectangle entourant l'image stockée dans le métafichier

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRecordSignature() {#getRecordSignature--}
```
public int getRecordSignature()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la signature de l'enregistrement. Cela DOIT être ENHMETA\_SIGNATURE, provenant de l'énumération FormatSignature (section 2.1.14).

**Returns:**
int
### setRecordSignature(int value) {#setRecordSignature-int-}
```
public void setRecordSignature(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la signature de l'enregistrement. Cela DOIT être ENHMETA\_SIGNATURE, provenant de l'énumération FormatSignature (section 2.1.14).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtient ou définit Version (4 octets) : un entier non signé de 32 bits qui spécifie l'interopérabilité du métafichier EMF. Cela DEVRAIT être 0x00010000

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtient ou définit Version (4 octets) : un entier non signé de 32 bits qui spécifie l'interopérabilité du métafichier EMF. Cela DEVRAIT être 0x00010000

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBytes() {#getBytes--}
```
public int getBytes()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille du métafichier, en octets.

**Returns:**
int
### setBytes(int value) {#setBytes-int-}
```
public void setBytes(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille du métafichier, en octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRecords() {#getRecords--}
```
public int getRecords()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'enregistrements dans le métafichier

**Returns:**
int
### setRecords(int value) {#setRecords-int-}
```
public void setRecords(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'enregistrements dans le métafichier

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHandles() {#getHandles--}
```
public short getHandles()
```


Obtient ou définit un entier non signé de 16 bits qui spécifie le nombre d'objets graphiques qui seront utilisés lors du traitement du métafichier

**Returns:**
short
### setHandles(short value) {#setHandles-short-}
```
public void setHandles(short value)
```


Obtient ou définit un entier non signé de 16 bits qui spécifie le nombre d'objets graphiques qui seront utilisés lors du traitement du métafichier

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Obtient ou définit un entier non signé de 16 bits qui DOIT être 0x0000 et DOIT être ignoré

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Obtient ou définit un entier non signé de 16 bits qui DOIT être 0x0000 et DOIT être ignoré

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getNDesription() {#getNDesription--}
```
public int getNDesription()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de caractères dans le tableau contenant la description du contenu du métafichier. C'est zéro s'il n'y a aucune chaîne de description.

**Returns:**
int
### setNDesription(int value) {#setNDesription-int-}
```
public void setNDesription(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de caractères dans le tableau contenant la description du contenu du métafichier. C'est zéro s'il n'y a aucune chaîne de description.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getOffDescription() {#getOffDescription--}
```
public int getOffDescription()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage depuis le début de cet enregistrement jusqu'au tableau contenant la description du contenu du métafichier

**Returns:**
int
### setOffDescription(int value) {#setOffDescription-int-}
```
public void setOffDescription(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage depuis le début de cet enregistrement jusqu'au tableau contenant la description du contenu du métafichier

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'entrées dans la palette du métafichier. La palette se trouve dans l'enregistrement EMR\_EOF

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'entrées dans la palette du métafichier. La palette se trouve dans l'enregistrement EMR\_EOF

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDevice() {#getDevice--}
```
public Size getDevice()
```


Obtient ou définit un objet WMF SizeL ([MS-WMF] section 2.2.2.22) qui spécifie la taille du dispositif de référence, en pixels

**Returns:**
[Size](../../com.aspose.imaging/size)
### setDevice(Size value) {#setDevice-com.aspose.imaging.Size-}
```
public void setDevice(Size value)
```


Obtient ou définit un objet WMF SizeL ([MS-WMF] section 2.2.2.22) qui spécifie la taille du dispositif de référence, en pixels

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getMillimeters() {#getMillimeters--}
```
public Size getMillimeters()
```


Obtient ou définit un objet WMF SizeL qui spécifie la taille du dispositif de référence, en millimètres

**Returns:**
[Size](../../com.aspose.imaging/size)
### setMillimeters(Size value) {#setMillimeters-com.aspose.imaging.Size-}
```
public void setMillimeters(Size value)
```


Obtient ou définit un objet WMF SizeL qui spécifie la taille du dispositif de référence, en millimètres

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getValid() {#getValid--}
```
public boolean getValid()
```


Obtient une valeur indiquant si cet `EmfHeaderObject` est valide.

Valeur : `true` si valide ; sinon, `false`.

**Returns:**
boolean

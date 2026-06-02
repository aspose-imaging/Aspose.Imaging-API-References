---
title: "EmfPlusImageAttributes"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusImageAttributes specifica come i colori dell'immagine bitmap vengono manipolati durante il rendering."
type: docs
weight: 48
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImageAttributes extends EmfPlusGraphicsObjectType
```

L'oggetto EmfPlusImageAttributes specifica come i colori dell'immagine bitmap vengono manipolati durante il rendering.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come gestire le condizioni di bordo con un valore dell'enumerazione WrapMode (sezione 2.1.1.34). |
| [setWrapMode(int value)](#setWrapMode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come gestire le condizioni di bordo con un valore dell'enumerazione WrapMode (sezione 2.1.1.34). |
| [getClampArgb32Color()](#getClampArgb32Color--) | Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore del bordo da utilizzare quando il valore WrapMode è WrapModeClamp. |
| [setClampArgb32Color(int value)](#setClampArgb32Color-int-) | Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore del bordo da utilizzare quando il valore WrapMode è WrapModeClamp. |
| [getObjectClamp()](#getObjectClamp--) | Ottiene o imposta un intero con segno a 32 bit che specifica il comportamento di bloccaggio dell'oggetto. |
| [setObjectClamp(int value)](#setObjectClamp-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica il comportamento di bloccaggio dell'oggetto. |
### EmfPlusImageAttributes() {#EmfPlusImageAttributes--}
```
public EmfPlusImageAttributes()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come gestire le condizioni di bordo con un valore dell'enumerazione WrapMode (sezione 2.1.1.34).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come gestire le condizioni di bordo con un valore dell'enumerazione WrapMode (sezione 2.1.1.34).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getClampArgb32Color() {#getClampArgb32Color--}
```
public int getClampArgb32Color()
```


Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore del bordo da utilizzare quando il valore WrapMode è WrapModeClamp. Questo colore è visibile quando il rettangolo di origine elaborato da un record EmfPlusDrawImage (sezione 2.3.4.8) è più grande dell'immagine stessa.

**Returns:**
int
### setClampArgb32Color(int value) {#setClampArgb32Color-int-}
```
public void setClampArgb32Color(int value)
```


Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore del bordo da utilizzare quando il valore WrapMode è WrapModeClamp. Questo colore è visibile quando il rettangolo di origine elaborato da un record EmfPlusDrawImage (sezione 2.3.4.8) è più grande dell'immagine stessa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getObjectClamp() {#getObjectClamp--}
```
public int getObjectClamp()
```


Ottiene o imposta un intero con segno a 32 bit che specifica il comportamento di bloccaggio dell'oggetto. Non viene utilizzato finché questo oggetto non viene applicato a un'immagine in fase di disegno. Questo valore DEVE essere uno dei valori definiti nella tabella seguente.

**Returns:**
int
### setObjectClamp(int value) {#setObjectClamp-int-}
```
public void setObjectClamp(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica il comportamento di bloccaggio dell'oggetto. Non viene utilizzato finché questo oggetto non viene applicato a un'immagine in fase di disegno. Questo valore DEVE essere uno dei valori definiti nella tabella seguente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


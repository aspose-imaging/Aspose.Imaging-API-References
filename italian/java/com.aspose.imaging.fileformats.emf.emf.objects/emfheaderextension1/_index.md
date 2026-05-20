---
title: "EmfHeaderExtension1"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto HeaderExtension1 definisce la prima estensione all'intestazione del metafile EMF."
type: docs
weight: 18
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
```
public final class EmfHeaderExtension1 extends EmfHeaderObject
```

L'oggetto HeaderExtension1 definisce la prima estensione all'intestazione del metafile EMF. Aggiunge il supporto per un oggetto PixelFormatDescriptor (sezione 2.2.22) e i record OpenGL [OPENGL] (sezione 2.3.9).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCbPixelFormat()](#getCbPixelFormat--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dell'oggetto PixelFormatDescriptor. |
| [setCbPixelFormat(int value)](#setCbPixelFormat-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dell'oggetto PixelFormatDescriptor. |
| [getOffPixelFormat()](#getOffPixelFormat--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'offset all'oggetto PixelFormatDescriptor. |
| [setOffPixelFormat(int value)](#setOffPixelFormat-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'offset all'oggetto PixelFormatDescriptor. |
| [getBOpenGl()](#getBOpenGl--) | Ottiene o imposta un intero senza segno a 32 bit che indica se i comandi OpenGL sono presenti nel metafile. |
| [setBOpenGl(int value)](#setBOpenGl-int-) | Ottiene o imposta un intero senza segno a 32 bit che indica se i comandi OpenGL sono presenti nel metafile. |
### EmfHeaderExtension1() {#EmfHeaderExtension1--}
```
public EmfHeaderExtension1()
```


### getCbPixelFormat() {#getCbPixelFormat--}
```
public int getCbPixelFormat()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dell'oggetto PixelFormatDescriptor. Questo DEVE essere 0x00000000 se non è impostato alcun formato pixel.

**Returns:**
int
### setCbPixelFormat(int value) {#setCbPixelFormat-int-}
```
public void setCbPixelFormat(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dell'oggetto PixelFormatDescriptor. Questo DEVE essere 0x00000000 se non è impostato alcun formato pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getOffPixelFormat() {#getOffPixelFormat--}
```
public int getOffPixelFormat()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'offset all'oggetto PixelFormatDescriptor. Questo DEVE essere 0x00000000 se non è impostato alcun formato pixel.

**Returns:**
int
### setOffPixelFormat(int value) {#setOffPixelFormat-int-}
```
public void setOffPixelFormat(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'offset all'oggetto PixelFormatDescriptor. Questo DEVE essere 0x00000000 se non è impostato alcun formato pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBOpenGl() {#getBOpenGl--}
```
public int getBOpenGl()
```


Ottiene o imposta un intero senza segno a 32 bit che indica se i comandi OpenGL sono presenti nel metafile. 0x00000000 i record OpenGL non sono presenti nel metafile. 0x00000001 i record OpenGL sono presenti nel metafile.

**Returns:**
int
### setBOpenGl(int value) {#setBOpenGl-int-}
```
public void setBOpenGl(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che indica se i comandi OpenGL sono presenti nel metafile. 0x00000000 i record OpenGL non sono presenti nel metafile. 0x00000001 i record OpenGL sono presenti nel metafile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


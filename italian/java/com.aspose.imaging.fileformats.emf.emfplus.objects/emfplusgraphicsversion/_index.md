---
title: "EmfPlusGraphicsVersion"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusGraphicsVersion specifica la versione della grafica del sistema operativo utilizzata per creare un metafile EMF."
type: docs
weight: 44
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusGraphicsVersion extends EmfPlusStructureObjectType
```

L'oggetto EmfPlusGraphicsVersion specifica la versione della grafica del sistema operativo utilizzata per creare un metafile EMF+.

Le versioni della grafica sono estensibili dal fornitore; tuttavia, per garantire l'interoperabilità, qualsiasi estensione DEVE essere implementata sia nei client sia nei server dei metafili EMF+.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusGraphicsVersion()](#EmfPlusGraphicsVersion--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMetafileSignature()](#getMetafileSignature--) | Ottiene una MetafileSignature (20 bit): un valore che identifica il tipo di metafile. |
| [setMetafileSignature(int value)](#setMetafileSignature-int-) | Ottiene una MetafileSignature (20 bit): un valore che identifica il tipo di metafile. |
| [getGraphicsVersion()](#getGraphicsVersion--) | Ottiene una GraphicsVersion (12 bit): la versione della grafica del sistema operativo. |
| [setGraphicsVersion(int value)](#setGraphicsVersion-int-) | Ottiene una GraphicsVersion (12 bit): la versione della grafica del sistema operativo. |
### EmfPlusGraphicsVersion() {#EmfPlusGraphicsVersion--}
```
public EmfPlusGraphicsVersion()
```


### getMetafileSignature() {#getMetafileSignature--}
```
public int getMetafileSignature()
```


Ottiene una MetafileSignature (20 bit): un valore che identifica il tipo di metafile. Il valore per un metafile EMF+ è 0xDBC01.

**Returns:**
int
### setMetafileSignature(int value) {#setMetafileSignature-int-}
```
public void setMetafileSignature(int value)
```


Ottiene una MetafileSignature (20 bit): un valore che identifica il tipo di metafile. Il valore per un metafile EMF+ è 0xDBC01.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getGraphicsVersion() {#getGraphicsVersion--}
```
public int getGraphicsVersion()
```


Ottiene una GraphicsVersion (12 bit): la versione della grafica del sistema operativo. Questo valore DEVE essere definito nell'enumerazione `EmfPlusGraphicsVersion`

**Returns:**
int
### setGraphicsVersion(int value) {#setGraphicsVersion-int-}
```
public void setGraphicsVersion(int value)
```


Ottiene una GraphicsVersion (12 bit): la versione della grafica del sistema operativo. Questo valore DEVE essere definito nell'enumerazione `EmfPlusGraphicsVersion`

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


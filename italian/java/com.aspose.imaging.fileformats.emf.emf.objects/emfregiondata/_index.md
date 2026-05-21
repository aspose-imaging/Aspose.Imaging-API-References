---
title: "EmfRegionData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto RegionData specifica i dati che definiscono una regione composta da rettangoli non sovrapposti."
type: docs
weight: 33
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionData extends EmfObject
```

L'oggetto RegionData specifica i dati che definiscono una regione, composta da rettangoli non sovrapposti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfRegionData()](#EmfRegionData--) | Inizializza una nuova istanza della classe `EmfRegionData`. |
| [EmfRegionData(Rectangle rectangle)](#EmfRegionData-com.aspose.imaging.Rectangle-) | Inizializza una nuova istanza della classe `EmfRegionData`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRegionDataHeader()](#getRegionDataHeader--) | Ottiene un oggetto RegionDataHeader a 256 bit che descrive i dati seguenti. |
| [setRegionDataHeader(EmfRegionDataHeader value)](#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-) | Imposta un oggetto RegionDataHeader a 256 bit che descrive i dati seguenti. |
| [getData()](#getData--) | Ottiene un array di oggetti WMF RectL ([MS-WMF] sezione 2.2.2.19); gli oggetti sono uniti per creare la regione |
| [setData(Rectangle[] value)](#setData-com.aspose.imaging.Rectangle---) | Imposta un array di oggetti WMF RectL ([MS-WMF] sezione 2.2.2.19); gli oggetti sono uniti per creare la regione |
### EmfRegionData() {#EmfRegionData--}
```
public EmfRegionData()
```


Inizializza una nuova istanza della classe `EmfRegionData`.

### EmfRegionData(Rectangle rectangle) {#EmfRegionData-com.aspose.imaging.Rectangle-}
```
public EmfRegionData(Rectangle rectangle)
```


Inizializza una nuova istanza della classe `EmfRegionData`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |

### getRegionDataHeader() {#getRegionDataHeader--}
```
public EmfRegionDataHeader getRegionDataHeader()
```


Ottiene un oggetto RegionDataHeader a 256 bit che descrive i dati seguenti.

**Returns:**
[EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader)
### setRegionDataHeader(EmfRegionDataHeader value) {#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-}
```
public void setRegionDataHeader(EmfRegionDataHeader value)
```


Imposta un oggetto RegionDataHeader a 256 bit che descrive i dati seguenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader) |  |

### getData() {#getData--}
```
public Rectangle[] getData()
```


Ottiene un array di oggetti WMF RectL ([MS-WMF] sezione 2.2.2.19); gli oggetti sono uniti per creare la regione

**Returns:**
com.aspose.imaging.Rectangle[]
### setData(Rectangle[] value) {#setData-com.aspose.imaging.Rectangle---}
```
public void setData(Rectangle[] value)
```


Imposta un array di oggetti WMF RectL ([MS-WMF] sezione 2.2.2.19); gli oggetti sono uniti per creare la regione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |


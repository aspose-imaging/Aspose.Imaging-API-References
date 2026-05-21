---
title: "EmfPlusStringFormatData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusStringFormatData specifica le tabulazioni e le posizioni dei caratteri per una stringa grafica."
type: docs
weight: 75
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusStringFormatData extends EmfPlusStructureObjectType
```

L'oggetto EmfPlusStringFormatData specifica le tabulazioni e le posizioni dei caratteri per una stringa grafica.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTabStops()](#getTabStops--) | Ottiene o imposta un array opzionale di valori a virgola mobile che specificano le posizioni opzionali delle tabulazioni per questo oggetto. |
| [setTabStops(float[] value)](#setTabStops-float---) | Ottiene o imposta un array opzionale di valori a virgola mobile che specificano le posizioni opzionali delle tabulazioni per questo oggetto. |
| [getCharRange()](#getCharRange--) | Ottiene o imposta un array opzionale di oggetti RangeCount EmfPlusCharacterRange che specificano l'intervallo delle posizioni dei caratteri all'interno di una stringa di testo. |
| [setCharRange(EmfPlusCharacterRange[] value)](#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---) | Ottiene o imposta un array opzionale di oggetti RangeCount EmfPlusCharacterRange che specificano l'intervallo delle posizioni dei caratteri all'interno di una stringa di testo. |
### EmfPlusStringFormatData() {#EmfPlusStringFormatData--}
```
public EmfPlusStringFormatData()
```


### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Ottiene o imposta un array opzionale di valori a virgola mobile che specificano le posizioni opzionali delle tabulazioni per questo oggetto. Ogni valore di tabulazione rappresenta il numero di spazi tra le tabulazioni o, per la prima tabulazione, il numero di spazi tra l'inizio di una riga di testo e la prima tabulazione. Questo campo DEVE essere presente se il valore del campo TabStopCount nell'oggetto EmfPlusStringFormat è maggiore di 0.

**Returns:**
float[]
### setTabStops(float[] value) {#setTabStops-float---}
```
public void setTabStops(float[] value)
```


Ottiene o imposta un array opzionale di valori a virgola mobile che specificano le posizioni opzionali delle tabulazioni per questo oggetto. Ogni valore di tabulazione rappresenta il numero di spazi tra le tabulazioni o, per la prima tabulazione, il numero di spazi tra l'inizio di una riga di testo e la prima tabulazione. Questo campo DEVE essere presente se il valore del campo TabStopCount nell'oggetto EmfPlusStringFormat è maggiore di 0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float[] |  |

### getCharRange() {#getCharRange--}
```
public EmfPlusCharacterRange[] getCharRange()
```


Ottiene o imposta un array opzionale di oggetti RangeCount EmfPlusCharacterRange che specificano l'intervallo delle posizioni dei caratteri all'interno di una stringa di testo. La regione di delimitazione è definita dall'area del display occupata da un gruppo di caratteri specificati dall'intervallo di caratteri. Questo campo DEVE essere presente se il valore del campo RangeCount nell'oggetto EmfPlusStringFormat è maggiore di 0.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange[]
### setCharRange(EmfPlusCharacterRange[] value) {#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---}
```
public void setCharRange(EmfPlusCharacterRange[] value)
```


Ottiene o imposta un array opzionale di oggetti RangeCount EmfPlusCharacterRange che specificano l'intervallo delle posizioni dei caratteri all'interno di una stringa di testo. La regione di delimitazione è definita dall'area del display occupata da un gruppo di caratteri specificati dall'intervallo di caratteri. Questo campo DEVE essere presente se il valore del campo RangeCount nell'oggetto EmfPlusStringFormat è maggiore di 0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusCharacterRange\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange) |  |


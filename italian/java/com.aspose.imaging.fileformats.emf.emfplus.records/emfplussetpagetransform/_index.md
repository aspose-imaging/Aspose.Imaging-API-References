---
title: "EmfPlusSetPageTransform"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusSetPageTransform specifica i fattori di scala e le unità per convertire le coordinate dello spazio pagina in coordinate dello spazio dispositivo."
type: docs
weight: 61
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetPageTransform extends EmfPlusTerminalServerRecordType
```

Il record EmfPlusSetPageTransform specifica i fattori di scala e le unità per convertire le coordinate dello spazio pagina in coordinate dello spazio dispositivo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusSetPageTransform(EmfPlusRecord source)](#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusSetPageTransform`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Ottiene l'unità di misura per le coordinate dello spazio pagina, dall'enumerazione UnitType (sezione 2.1.1.33). |
| [getPageScale()](#getPageScale--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala per la conversione delle coordinate dello spazio pagina in coordinate dello spazio dispositivo. |
| [setPageScale(float value)](#setPageScale-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala per la conversione delle coordinate dello spazio pagina in coordinate dello spazio dispositivo. |
### EmfPlusSetPageTransform(EmfPlusRecord source) {#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetPageTransform(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusSetPageTransform`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Ottiene l'unità di misura per le coordinate dello spazio pagina, dall'enumerazione UnitType (sezione 2.1.1.33). Questo valore NON DEVE essere UnitTypeDisplay o UnitTypeWorld.

Valore: L'unità di pagina.

**Returns:**
int
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala per la conversione delle coordinate dello spazio pagina in coordinate dello spazio dispositivo.

Valore: la scala della pagina.

**Returns:**
float
### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala per la conversione delle coordinate dello spazio pagina in coordinate dello spazio dispositivo.

Valore: la scala della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |


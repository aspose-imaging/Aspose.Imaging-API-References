---
title: "EmfLogBrushEx"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto LogBrushEx definisce lo stile, il colore e il motivo di un pennello indipendente dal dispositivo."
type: docs
weight: 21
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfLogBrushEx extends EmfObject
```

L'oggetto LogBrushEx definisce lo stile, il colore e il motivo di un pennello indipendente dal dispositivo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfLogBrushEx()](#EmfLogBrushEx--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBrushStyle()](#getBrushStyle--) | Ottiene o imposta un 32-bit unsigned integer che specifica lo stile del pennello. |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Ottiene o imposta un 32-bit unsigned integer che specifica lo stile del pennello. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Ottiene o imposta un oggetto 32-bit WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica un colore. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Ottiene o imposta un oggetto 32-bit WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica un colore. |
| [getBrushHatch()](#getBrushHatch--) | Ottiene o imposta un campo unsigned a 32 bit che contiene i dati di tratteggio del pennello. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Ottiene o imposta un campo unsigned a 32 bit che contiene i dati di tratteggio del pennello. |
### EmfLogBrushEx() {#EmfLogBrushEx--}
```
public EmfLogBrushEx()
```


### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Ottiene o imposta un 32-bit unsigned integer che specifica lo stile del pennello. Il valore DEVE essere una enumerazione della enumerazione WMF BrushStyle ([MS-WMF] sezione 2.1.1.4). I valori di stile supportati in questa struttura sono elencati più avanti in questa sezione. Lo stile BS\_NULL DOVREBBE essere usato per specificare un pennello che non ha effetto.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Ottiene o imposta un 32-bit unsigned integer che specifica lo stile del pennello. Il valore DEVE essere una enumerazione della enumerazione WMF BrushStyle ([MS-WMF] sezione 2.1.1.4). I valori di stile supportati in questa struttura sono elencati più avanti in questa sezione. Lo stile BS\_NULL DOVREBBE essere usato per specificare un pennello che non ha effetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Ottiene o imposta un oggetto 32-bit WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica un colore. L'interpretazione di questo campo dipende dal valore di BrushStyle, come spiegato nella tabella seguente.

Valore: Il colore ARGB a 32 bit

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Ottiene o imposta un oggetto 32-bit WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica un colore. L'interpretazione di questo campo dipende dal valore di BrushStyle, come spiegato nella tabella seguente.

Valore: Il colore ARGB a 32 bit

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Ottiene o imposta un campo unsigned a 32 bit che contiene i dati di tratteggio del pennello. La sua interpretazione dipende dal valore di BrushStyle,

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Ottiene o imposta un campo unsigned a 32 bit che contiene i dati di tratteggio del pennello. La sua interpretazione dipende dal valore di BrushStyle,

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


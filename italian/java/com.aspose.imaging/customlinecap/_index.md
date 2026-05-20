---
title: "CustomLineCap"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Incapsula un'estremità di linea personalizzata definita dall'utente."
type: docs
weight: 35
url: /it/java/com.aspose.imaging/customlinecap/
---
**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Incapsula un'estremità di linea personalizzata definita dall'utente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-) | Inizializza una nuova istanza della classe `CustomLineCap` con il contorno e il riempimento specificati. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-) | Inizializza una nuova istanza della classe `CustomLineCap` dall'enumerazione `LineCap` esistente specificata con il contorno e il riempimento specificati. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-) | Inizializza una nuova istanza della classe `CustomLineCap` dall'enumerazione `LineCap` esistente specificata con il contorno, il riempimento e l'inserimento specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillPath()](#getFillPath--) | Restituisce l'oggetto che definisce il riempimento per il cap personalizzato. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.imaging.GraphicsPath-) | Imposta l'oggetto che definisce il riempimento per il cap personalizzato. |
| [getStrokePath()](#getStrokePath--) | Restituisce l'oggetto che definisce il contorno del cap personalizzato. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.imaging.GraphicsPath-) | Imposta l'oggetto che definisce il contorno del cap personalizzato. |
| [getStrokeJoin()](#getStrokeJoin--) | Restituisce l'enumerazione `LineJoin` che determina come le linee che compongono questo oggetto `CustomLineCap` vengono unite. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Imposta l'enumerazione `LineJoin` che determina come le linee che compongono questo oggetto `CustomLineCap` vengono unite. |
| [getBaseCap()](#getBaseCap--) | Restituisce l'enumerazione `LineCap` su cui si basa questo `CustomLineCap`. |
| [setBaseCap(int value)](#setBaseCap-int-) | Imposta l'enumerazione `LineCap` su cui si basa questo `CustomLineCap`. |
| [getBaseInset()](#getBaseInset--) | Restituisce la distanza tra il cap e la linea. |
| [setBaseInset(float value)](#setBaseInset-float-) | Imposta la distanza tra il cap e la linea. |
| [getWidthScale()](#getWidthScale--) | Restituisce la quantità con cui scalare questo oggetto di classe `CustomLineCap` rispetto alla larghezza dell'oggetto `System.Drawing.Pen`. |
| [setWidthScale(float value)](#setWidthScale-float-) | Imposta la quantità con cui scalare questo oggetto di classe `CustomLineCap` rispetto alla larghezza dell'oggetto `System.Drawing.Pen`. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Imposta i cap usati per avviare e terminare le linee che compongono questo cap personalizzato. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Restituisce i cap usati per avviare e terminare le linee che compongono questo cap personalizzato. |
| [equals(Object o)](#equals-java.lang.Object-) | Verifica se gli oggetti sono uguali. |
| [hashCode()](#hashCode--) | Ottieni il codice hash dell'oggetto corrente. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Inizializza una nuova istanza della classe `CustomLineCap` con il contorno e il riempimento specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un oggetto `GraphicsPath` che definisce il riempimento per il cap personalizzato. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un oggetto `GraphicsPath` che definisce il contorno del cap personalizzato. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Inizializza una nuova istanza della classe `CustomLineCap` dall'enumerazione `LineCap` esistente specificata con il contorno e il riempimento specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un oggetto `GraphicsPath` che definisce il riempimento per il cap personalizzato. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un oggetto `GraphicsPath` che definisce il contorno del cap personalizzato. |
| baseCap | int | Il cap di linea da cui creare il cap personalizzato. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Inizializza una nuova istanza della classe `CustomLineCap` dall'enumerazione `LineCap` esistente specificata con il contorno, il riempimento e l'inserimento specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un oggetto `GraphicsPath` che definisce il riempimento per il cap personalizzato. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un oggetto `GraphicsPath` che definisce il contorno del cap personalizzato. |
| baseCap | int | Il cap di linea da cui creare il cap personalizzato. |
| baseInset | float | La distanza tra il cap e la linea. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Restituisce l'oggetto che definisce il riempimento per il cap personalizzato.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the fill for the custom cap.
### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.imaging.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Imposta l'oggetto che definisce il riempimento per il cap personalizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | L'oggetto che definisce il riempimento per il cap personalizzato. |

### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Restituisce l'oggetto che definisce il contorno del cap personalizzato.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the outline of the custom cap.
### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.imaging.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Imposta l'oggetto che definisce il contorno del cap personalizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | L'oggetto che definisce il contorno del cap personalizzato. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Restituisce l'enumerazione `LineJoin` che determina come le linee che compongono questo oggetto `CustomLineCap` vengono unite.

**Returns:**
int - L'enumerazione `LineJoin` che questo oggetto `CustomLineCap` utilizza per unire le linee.
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Imposta l'enumerazione `LineJoin` che determina come le linee che compongono questo oggetto `CustomLineCap` vengono unite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'enumerazione `LineJoin` che questo oggetto `CustomLineCap` utilizza per unire le linee. |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Restituisce l'enumerazione `LineCap` su cui si basa questo `CustomLineCap`.

**Returns:**
int - L'enumerazione `LineCap` su cui si basa questo `CustomLineCap`.
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Imposta l'enumerazione `LineCap` su cui si basa questo `CustomLineCap`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'enumerazione `LineCap` su cui si basa questo `CustomLineCap`. |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Restituisce la distanza tra il cap e la linea.

**Returns:**
float - La distanza tra l'inizio del cap e la fine della linea.
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Imposta la distanza tra il cap e la linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | La distanza tra l'inizio del cap e la fine della linea. |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Restituisce la quantità con cui scalare questo oggetto di classe `CustomLineCap` rispetto alla larghezza dell'oggetto `System.Drawing.Pen`.

**Returns:**
float - La quantità di cui scalare il cap.
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Imposta la quantità con cui scalare questo oggetto di classe `CustomLineCap` rispetto alla larghezza dell'oggetto `System.Drawing.Pen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | La quantità di cui scalare il cap. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Imposta i cap usati per avviare e terminare le linee che compongono questo cap personalizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startCap | int | L'enumerazione `LineCap` utilizzata all'inizio di una linea all'interno di questo cap. |
| endCap | int | L'enumerazione `LineCap` utilizzata alla fine di una linea all'interno di questo cap. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Restituisce i cap usati per avviare e terminare le linee che compongono questo cap personalizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startCap | int[] | L'enumerazione `LineCap` utilizzata all'inizio di una linea all'interno di questo cap. |
| endCap | int[] | L'enumerazione `LineCap` utilizzata alla fine di una linea all'interno di questo cap. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Verifica se gli oggetti sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| o | java.lang.Object | L'altro oggetto. |

**Returns:**
boolean - Il risultato del confronto di uguaglianza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottieni il codice hash dell'oggetto corrente.

**Returns:**
int - Il codice hash.

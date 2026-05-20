---
title: "WmfSetTextCharExtra"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record META_SETTEXTCHAREXTRA definisce la spaziatura intercarattere per la giustificazione del testo nel contesto del dispositivo di riproduzione."
type: docs
weight: 86
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfsettextcharextra/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetTextCharExtra extends WmfObject
```

Il record META\_SETTEXTCHAREXTRA definisce la spaziatura intercarattere per la giustificazione del testo nel contesto del dispositivo di riproduzione. La spaziatura viene aggiunta allo spazio bianco tra ogni carattere, inclusi i caratteri ``, quando viene emessa una riga di testo giustificato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfSetTextCharExtra()](#WmfSetTextCharExtra--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCharExtra()](#getCharExtra--) | Ottiene o imposta lo spazio extra del carattere. |
| [setCharExtra(int value)](#setCharExtra-int-) | Ottiene o imposta lo spazio extra del carattere. |
### WmfSetTextCharExtra() {#WmfSetTextCharExtra--}
```
public WmfSetTextCharExtra()
```


### getCharExtra() {#getCharExtra--}
```
public int getCharExtra()
```


Ottiene o imposta lo spazio extra del carattere.

Valore: La quantità di spazio extra, in unità logiche, da aggiungere a ogni carattere. Se la modalità di mappatura corrente non è MM\_TEXT, questo valore viene trasformato e arrotondato al pixel più vicino. Per dettagli su come impostare la modalità di mappatura, vedere META\_SETMAPMODE (sezione 2.3.5.17).

**Returns:**
int
### setCharExtra(int value) {#setCharExtra-int-}
```
public void setCharExtra(int value)
```


Ottiene o imposta lo spazio extra del carattere.

Valore: La quantità di spazio extra, in unità logiche, da aggiungere a ogni carattere. Se la modalità di mappatura corrente non è MM\_TEXT, questo valore viene trasformato e arrotondato al pixel più vicino. Per dettagli su come impostare la modalità di mappatura, vedere META\_SETMAPMODE (sezione 2.3.5.17).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


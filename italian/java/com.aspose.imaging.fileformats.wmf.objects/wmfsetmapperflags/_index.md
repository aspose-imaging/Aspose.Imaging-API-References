---
title: "WmfSetMapperFlags"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record META_SETMAPPERFLAGS definisce l'algoritmo che il mapper dei font utilizza quando mappa i font logici a quelli fisici."
type: docs
weight: 78
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetMapperFlags extends WmfObject
```

Il record META\_SETMAPPERFLAGS definisce l'algoritmo che il mapper dei caratteri utilizza quando mappa i font logici ai font fisici.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfSetMapperFlags()](#WmfSetMapperFlags--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMapperValues()](#getMapperValues--) | Ottiene o imposta i valori del mapper. |
| [setMapperValues(int value)](#setMapperValues-int-) | Ottiene o imposta i valori del mapper. |
### WmfSetMapperFlags() {#WmfSetMapperFlags--}
```
public WmfSetMapperFlags()
```


### getMapperValues() {#getMapperValues--}
```
public int getMapperValues()
```


Ottiene o imposta i valori del mapper.

Valore: Il mapper dei font tenta di far corrispondere il rapporto d'aspetto di un font al rapporto d'aspetto del dispositivo corrente. Se il bit zero è impostato, il mapper seleziona solo i font corrispondenti.

**Returns:**
int
### setMapperValues(int value) {#setMapperValues-int-}
```
public void setMapperValues(int value)
```


Ottiene o imposta i valori del mapper.

Valore: Il mapper dei font tenta di far corrispondere il rapporto d'aspetto di un font al rapporto d'aspetto del dispositivo corrente. Se il bit zero è impostato, il mapper seleziona solo i font corrispondenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


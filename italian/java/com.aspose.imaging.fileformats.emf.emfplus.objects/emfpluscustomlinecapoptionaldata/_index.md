---
title: "EmfPlusCustomLineCapOptionalData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusCustomLineCapOptionalData specifica dati opzionali di riempimento e contorno per un capolinea personalizzato."
type: docs
weight: 37
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusCustomLineCapOptionalData extends EmfPlusStructureObjectType
```

L'oggetto EmfPlusCustomLineCapOptionalData specifica dati opzionali di riempimento e contorno per un capolinea personalizzato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusCustomLineCapOptionalData()](#EmfPlusCustomLineCapOptionalData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillData()](#getFillData--) | Ottiene o imposta l'oggetto opzionale EmfPlusFillPath (sezione 2.2.2.17) che specifica il percorso per riempire un custom graphics line cap. |
| [setFillData(EmfPlusFillPath value)](#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-) | Ottiene o imposta l'oggetto opzionale EmfPlusFillPath (sezione 2.2.2.17) che specifica il percorso per riempire un custom graphics line cap. |
| [getOutlineData()](#getOutlineData--) | Ottiene o imposta l'oggetto opzionale EmfPlusLinePath (sezione 2.2.2.26) che specifica il percorso per delineare un custom graphics line cap. |
| [setOutlineData(EmfPlusLinePath value)](#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-) | Ottiene o imposta l'oggetto opzionale EmfPlusLinePath (sezione 2.2.2.26) che specifica il percorso per delineare un custom graphics line cap. |
### EmfPlusCustomLineCapOptionalData() {#EmfPlusCustomLineCapOptionalData--}
```
public EmfPlusCustomLineCapOptionalData()
```


### getFillData() {#getFillData--}
```
public EmfPlusFillPath getFillData()
```


Ottiene o imposta l'oggetto opzionale EmfPlusFillPath (sezione 2.2.2.17) che specifica il percorso per riempire un custom graphics line cap. Questo campo DEVE essere presente se il flag CustomLineCapDataFillPath è impostato nel campo CustomLineCapDataFlags dell'oggetto EmfPlusCustomLineCapData.

**Returns:**
[EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath)
### setFillData(EmfPlusFillPath value) {#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-}
```
public void setFillData(EmfPlusFillPath value)
```


Ottiene o imposta l'oggetto opzionale EmfPlusFillPath (sezione 2.2.2.17) che specifica il percorso per riempire un custom graphics line cap. Questo campo DEVE essere presente se il flag CustomLineCapDataFillPath è impostato nel campo CustomLineCapDataFlags dell'oggetto EmfPlusCustomLineCapData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath) |  |

### getOutlineData() {#getOutlineData--}
```
public EmfPlusLinePath getOutlineData()
```


Ottiene o imposta l'oggetto opzionale EmfPlusLinePath (sezione 2.2.2.26) che specifica il percorso per delineare un custom graphics line cap. Questo campo DEVE essere presente se il flag CustomLineCapDataLinePath è impostato nel campo CustomLineCapDataFlags dell'oggetto EmfPlusCustomLineCapData.

**Returns:**
[EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath)
### setOutlineData(EmfPlusLinePath value) {#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-}
```
public void setOutlineData(EmfPlusLinePath value)
```


Ottiene o imposta l'oggetto opzionale EmfPlusLinePath (sezione 2.2.2.26) che specifica il percorso per delineare un custom graphics line cap. Questo campo DEVE essere presente se il flag CustomLineCapDataLinePath è impostato nel campo CustomLineCapDataFlags dell'oggetto EmfPlusCustomLineCapData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath) |  |


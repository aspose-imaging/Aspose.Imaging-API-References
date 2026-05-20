---
title: "EmfPlusRedEyeCorrectionEffect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto RedEyeCorrectionEffect specifica le aree di un'immagine a cui viene applicata una correzione degli occhi rossi."
type: docs
weight: 67
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusredeyecorrectioneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusRedEyeCorrectionEffect extends EmfPlusImageEffectsObjectType
```

L'oggetto RedEyeCorrectionEffect specifica le aree di un'immagine a cui viene applicata una correzione degli occhi rossi.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusRedEyeCorrectionEffect()](#EmfPlusRedEyeCorrectionEffect--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNumberOfAreas()](#getNumberOfAreas--) | Ottiene o imposta l'intero a 32 bit con segno che specifica il numero di rettangoli nel campo Areas. |
| [setNumberOfAreas(int value)](#setNumberOfAreas-int-) | Ottiene o imposta l'intero a 32 bit con segno che specifica il numero di rettangoli nel campo Areas. |
| [getAreas()](#getAreas--) | Ottiene o imposta l'array di oggetti NumberOfAreas WMF RectL, specificati nella sezione 2.2.2.19 di [MS-WMF]. |
| [setAreas(Rectangle[] value)](#setAreas-com.aspose.imaging.Rectangle---) | Ottiene o imposta l'array di oggetti NumberOfAreas WMF RectL, specificati nella sezione 2.2.2.19 di [MS-WMF]. |
### EmfPlusRedEyeCorrectionEffect() {#EmfPlusRedEyeCorrectionEffect--}
```
public EmfPlusRedEyeCorrectionEffect()
```


### getNumberOfAreas() {#getNumberOfAreas--}
```
public int getNumberOfAreas()
```


Ottiene o imposta l'intero a 32 bit con segno che specifica il numero di rettangoli nel campo Areas.

Valore: Il numero di aree.

**Returns:**
int
### setNumberOfAreas(int value) {#setNumberOfAreas-int-}
```
public void setNumberOfAreas(int value)
```


Ottiene o imposta l'intero a 32 bit con segno che specifica il numero di rettangoli nel campo Areas.

Valore: Il numero di aree.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getAreas() {#getAreas--}
```
public Rectangle[] getAreas()
```


Ottiene o imposta l'array di oggetti NumberOfAreas WMF RectL, specificati nella sezione [MS-WMF] 2.2.2.19. Ogni rettangolo specifica un'area dell'immagine bitmap a cui l'effetto di correzione del rosso occhio DEVE essere applicato.

Valore: Le aree.

**Returns:**
com.aspose.imaging.Rectangle[]
### setAreas(Rectangle[] value) {#setAreas-com.aspose.imaging.Rectangle---}
```
public void setAreas(Rectangle[] value)
```


Ottiene o imposta l'array di oggetti NumberOfAreas WMF RectL, specificati nella sezione [MS-WMF] 2.2.2.19. Ogni rettangolo specifica un'area dell'immagine bitmap a cui l'effetto di correzione del rosso occhio DEVE essere applicato.

Valore: Le aree.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |


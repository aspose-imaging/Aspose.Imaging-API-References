---
title: "EmfBlendFunction Classe"
type: docs
weight: 90
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---

**Summary:** A structure that specifies the blending operations for source and destination bitmaps.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfBlendFunction()](#EmfBlendFunction__1) | Inizializza una nuova istanza della classe EmfBlendFunction |
| [EmfBlendFunction(dword_data)](#EmfBlendFunction_dword_data_2) | Inizializza una nuova istanza della classe [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| alpha_format | [EmfBlendFunction+AlphaFormatEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction+alphaformatenum/) | r | Ottiene una struttura che specifica come i pixel sorgente e destinazione sono <br/>            interpretati rispetto alla trasparenza alfa. |
| blend_flags | System.Byte | r | Ottiene i flag di fusione.<br/>            Questo valore DEVE essere 0x00 e DEVE essere ignorato. |
| blend_operation | System.Byte | r | Ottiene il codice dell'operazione di fusione. <br/>            L'unica operazione di fusione sorgente e destinazione <br/>            che è stata definita è 0x00, che specifica che il bitmap sorgente <br/>            DEVE essere combinato con il bitmap di destinazione basandosi sui valori di trasparenza alfa <br/>            dei pixel sorgente. Vedere le seguenti equazioni per i dettagli. |
| src_constant_alpha | System.Byte | r | Ottiene un intero senza segno a 8 bit che specifica la trasparenza alfa, <br/>            che determina la fusione dei bitmap sorgente e destinazione. Questo valore DEVE essere <br/>            usato sull'intero bitmap sorgente. Il valore minimo di trasparenza alfa, zero, <br/>            corrisponde a completamente trasparente, il valore massimo, 0xFF, corrisponde a <br/>            completamente opaco. In pratica, un valore di 0xFF specifica che i valori alfa per pixel <br/>            determinano la fusione dei bitmap sorgente e destinazione. Vedere le equazioni più avanti in <br/>            questa sezione per i dettagli. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [to_int()](#to_int__1) | Converte la rappresentazione stringa di un numero in un intero. |


### Constructor: EmfBlendFunction() {#EmfBlendFunction__1}


```
 EmfBlendFunction() 
```

Inizializza una nuova istanza della classe EmfBlendFunction

### Constructor: EmfBlendFunction(dword_data) {#EmfBlendFunction_dword_data_2}


```
 EmfBlendFunction(dword_data) 
```

Inizializza una nuova istanza della classe [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dword_data | int | I dati dword. |

### Method: to_int() {#to_int__1}


```
 to_int() 
```

Converte la rappresentazione stringa di un numero in un intero.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il valore DWORD della struttura. |



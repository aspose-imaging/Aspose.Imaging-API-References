---
title: "EmfPlusDrawDriverString Classe"
type: docs
weight: 110
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---

**Summary:** The EmfPlusDrawDriverString record specifies text output with character positions.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawDriverString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusDrawDriverString(source)](#EmfPlusDrawDriverString_source_1) | Inizializza una nuova istanza della classe [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Ottiene o imposta l'identificatore del pennello<br/> Un intero senza segno a 32 bit che specifica o il colore di primo piano del testo o un pennello grafico,<br/> a seconda del valore del flag S nei Flags. |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| driver_string_options_flags | [EmfPlusDriverStringOptionsFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/) | r/w | Ottiene o imposta i flag delle opzioni della stringa del driver<br/> Un intero senza segno a 32 bit che specifica la spaziatura, l'orientamento e la qualità del rendering per la stringa. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| glyph_count | int | r/w | Ottiene o imposta il conteggio dei glifi<br/> Un intero senza segno a 32 bit che specifica il numero di glifi nella stringa. |
| glyph_pos | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta l'array delle posizioni dei glifi<br/> Un array di oggetti EmfPlusPointF (sezione 2.2.2.36) che specificano la posizione di output di ogni glifo di carattere.<br/> DEVONO esserci elementi GlyphCount, che hanno una corrispondenza uno-a-uno con gli elementi dell'array Glyphs.<br/> Le posizioni dei glifi sono calcolate dalla posizione del primo glifo se il flag DriverStringOptionsRealizedAdvance<br/> nei flag DriverStringOptions è impostato. In questo caso, GlyphPos specifica solo la posizione del primo glifo. |
| glyphs | int[] | r/w | Ottiene o imposta l'array dei glifi<br/> Un array di valori a 16 bit che definiscono la stringa di testo da disegnare.<br/> Se il flag DriverStringOptionsCmapLookup nel campo DriverStringOptionsFlags è impostato, ogni valore in questo<br/> array specifica un carattere Unicode. Altrimenti, ogni valore specifica un indice a un<br/> glifo di carattere nell'oggetto EmfPlusFont specificato dal valore ObjectId nel campo Flags. |
| is_color | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è un colore.<br/> Questo bit indica il tipo di dati nel campo BrushId.<br/> Se impostato, BrushId specifica il valore colore in un oggetto EmfPlusARGB<br/> (sezione 2.2.2.1). Se non impostato, BrushId contiene l'indice della Tabella Oggetti EMF+<br/> di un oggetto EmfPlusBrush (sezione 2.1.1). |
| matrix_present | int | r/w | Ottiene o imposta il flag di presenza della matrice<br/> Un intero senza segno a 32 bit che specifica se una matrice di trasformazione è presente nel campo TransformMatrix<br/> 0 - nessuna matrice presente. 1 - la matrice di trasformazione è nel campo TransformMatrix |
| object_id | System.Byte | r/w | Ottiene o imposta l'identificatore dell'oggetto.<br/> L'indice della Tabella Oggetti EMF+ di un oggetto ***EmfPlusFont*** (sezione<br/> 2.2.1.3) per renderizzare il testo. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta la matrice di trasformazione<br/> Un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica la trasformazione da applicare a<br/> ogni valore nell'array di testo. La presenza di questi dati è determinata dal campo MatrixPresent. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusDrawDriverString(source) {#EmfPlusDrawDriverString_source_1}


```
 EmfPlusDrawDriverString(source) 
```

Inizializza una nuova istanza della classe [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/)

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |


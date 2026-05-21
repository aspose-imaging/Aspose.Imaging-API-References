---
title: "EmfPlusLanguageIdentifier"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusLanguageIdentifier specifica un identificatore di lingua che corrisponde alla lingua naturale in una località, includendo paesi, regioni geografiche e distretti amministrativi."
type: docs
weight: 50
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLanguageIdentifier extends EmfPlusStructureObjectType
```

L'oggetto EmfPlusLanguageIdentifier specifica un identificatore di lingua che corrisponde alla lingua naturale in una località, includendo paesi, regioni geografiche e distretti amministrativi. Ogni identificatore di lingua è una codifica di un valore di lingua primaria e di un valore di sottolinguaggio.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValue()](#getValue--) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 bit): Il paese, la regione geografica o il distretto amministrativo per la lingua naturale specificata nel campo PrimaryLanguageId. |
| [setValue(short value)](#setValue-short-) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 bit): Il paese, la regione geografica o il distretto amministrativo per la lingua naturale specificata nel campo PrimaryLanguageId. |
### EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier--}
```
public EmfPlusLanguageIdentifier()
```


### getValue() {#getValue--}
```
public short getValue()
```


Ottiene o imposta il valore del campo 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 bit): Il paese, la regione geografica o il distretto amministrativo per la lingua naturale specificata nel campo PrimaryLanguageId. Gli identificatori di sottolinguaggio sono estensibili dal fornitore. Gli identificatori di sottolinguaggio definiti dal fornitore DEVONO essere nell'intervallo 0x20 a 0x3F, inclusi. PrimaryLanguageId (10 bit): La lingua naturale. Gli identificatori di lingua primaria sono estensibili dal fornitore. Gli identificatori di lingua primaria definiti dal fornitore DEVONO essere nell'intervallo 0x0200 a 0x03FF, inclusi.

**Returns:**
short
### setValue(short value) {#setValue-short-}
```
public void setValue(short value)
```


Ottiene o imposta il valore del campo 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 bit): Il paese, la regione geografica o il distretto amministrativo per la lingua naturale specificata nel campo PrimaryLanguageId. Gli identificatori di sottolinguaggio sono estensibili dal fornitore. Gli identificatori di sottolinguaggio definiti dal fornitore DEVONO essere nell'intervallo 0x20 a 0x3F, inclusi. PrimaryLanguageId (10 bit): La lingua naturale. Gli identificatori di lingua primaria sono estensibili dal fornitore. Gli identificatori di lingua primaria definiti dal fornitore DEVONO essere nell'intervallo 0x0200 a 0x03FF, inclusi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |


---
title: "EmfPlusLanguageIdentifier"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusLanguageIdentifier spécifie un identifiant de langue qui correspond à la langue naturelle dans un paramètre régional incluant les pays, les régions géographiques et les districts administratifs."
type: docs
weight: 50
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLanguageIdentifier extends EmfPlusStructureObjectType
```

L'objet EmfPlusLanguageIdentifier spécifie un identifiant de langue qui correspond à la langue naturelle dans un paramètre régional, incluant les pays, les régions géographiques et les districts administratifs. Chaque identifiant de langue est un codage d’une valeur de langue principale et d’une valeur de sous‑langue.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValue()](#getValue--) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 bits) : Le pays, la région géographique ou le district administratif pour la langue naturelle spécifiée dans le champ PrimaryLanguageId. |
| [setValue(short value)](#setValue-short-) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 bits) : Le pays, la région géographique ou le district administratif pour la langue naturelle spécifiée dans le champ PrimaryLanguageId. |
### EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier--}
```
public EmfPlusLanguageIdentifier()
```


### getValue() {#getValue--}
```
public short getValue()
```


Obtient ou définit la valeur du champ 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 bits) : Le pays, la région géographique ou le district administratif pour la langue naturelle spécifiée dans le champ PrimaryLanguageId. Les identifiants de sous‑langue sont extensibles par le fournisseur. Les identifiants de sous‑langue définis par le fournisseur DOIVENT être dans la plage 0x20 à 0x3F, inclusive. PrimaryLanguageId (10 bits) : La langue naturelle. Les identifiants de langue principale sont extensibles par le fournisseur. Les identifiants de langue principale définis par le fournisseur DOIVENT être dans la plage 0x0200 à 0x03FF, inclusive.

**Returns:**
short
### setValue(short value) {#setValue-short-}
```
public void setValue(short value)
```


Obtient ou définit la valeur du champ 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 bits) : Le pays, la région géographique ou le district administratif pour la langue naturelle spécifiée dans le champ PrimaryLanguageId. Les identifiants de sous‑langue sont extensibles par le fournisseur. Les identifiants de sous‑langue définis par le fournisseur DOIVENT être dans la plage 0x20 à 0x3F, inclusive. PrimaryLanguageId (10 bits) : La langue naturelle. Les identifiants de langue principale sont extensibles par le fournisseur. Les identifiants de langue principale définis par le fournisseur DOIVENT être dans la plage 0x0200 à 0x03FF, inclusive.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |


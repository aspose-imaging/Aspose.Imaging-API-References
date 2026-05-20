---
title: "Mesuré"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Fournit des méthodes mesurées pour l'intégration"
type: docs
weight: 74
url: /fr/java/com.aspose.imaging/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Fournit des méthodes mesurées pour l'intégration

Dans cet exemple, une tentative sera faite pour définir la clé publique et privée mesurée

`// the component jar file: Metered metered = new Metered(); metered.setMeteredKey("PublicKey", "PrivateKey"); `
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Metered()](#Metered--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Obtient la taille du fichier de consommation |
| [getConsumptionCredit()](#getConsumptionCredit--) | Obtient le crédit de consommation |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Définit la clé publique et privée mesurée. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'Object spécifié est égal à cette instance. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Obtient la taille du fichier de consommation

**Returns:**
java.math.BigDecimal - taille du fichier de consommation
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Obtient le crédit de consommation

**Returns:**
java.math.BigDecimal - quantité de consommation
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Définit la clé publique et privée mesurée.

Si vous achetez une licence mesurée, au démarrage de l'application, cette API doit être appelée ; normalement, cela suffit. Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation. Pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence ; s'il est en statut d'évaluation, appelez à nouveau cette API.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | clé publique |
| privateKey | java.lang.String | clé privée |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'Object spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'Object à comparer avec cette instance. |

**Returns:**
boolean - `true` si l'Object spécifié est égal à cette instance ; sinon, `false`.

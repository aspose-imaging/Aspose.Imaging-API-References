---
title: "Classe Metered"
type: docs
weight: 6150
url: /fr/python-net/aspose.imaging/metered/
---

**Summary:** Provides metered methods for integration

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Metered

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Metered()](#Metered__1) | Initialise une nouvelle instance de cette classe. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Obtient le crédit de consommation |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Obtient la taille du fichier de consommation |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_3) | Définit la clé publique et privée mesurée.<br/>            Si vous achetez une licence mesurée, au démarrage de l'application, cette API doit être appelée, normalement, cela suffit. <br/>            Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation, <br/>            pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence ; s'il est en statut d'évaluation, appelez à nouveau cette API. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Initialise une nouvelle instance de cette classe.

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Obtient le crédit de consommation

**Returns**

| Type | Description |
| :- | :- |
| System.Decimal | quantité de consommation |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Obtient la taille du fichier de consommation

**Returns**

| Type | Description |
| :- | :- |
| System.Decimal | quantité de consommation |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_3}


```
 set_metered_key(public_key, private_key) 
```

Définit la clé publique et privée mesurée.<br/>            Si vous achetez une licence mesurée, au démarrage de l'application, cette API doit être appelée, normalement, cela suffit. <br/>            Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation, <br/>            pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence ; s'il est en statut d'évaluation, appelez à nouveau cette API.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| public_key | string | clé publique |
| private_key | string | clé privée |


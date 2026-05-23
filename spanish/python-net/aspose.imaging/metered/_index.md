---
title: "Clase Metered"
type: docs
weight: 6150
url: /es/python-net/aspose.imaging/metered/
---

**Summary:** Provides metered methods for integration

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Metered

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Metered()](#Metered__1) | Inicializa una nueva instancia de esta clase. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Obtiene crédito de consumo |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Obtiene el tamaño del archivo de consumo |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_3) | Establece la clave pública y privada con licencia medida.<br/>            Si compra una licencia medida, al iniciar la aplicación, debe llamarse a esta API; normalmente, eso es suficiente. <br/>            Sin embargo, si siempre falla la carga de los datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación, <br/>            para evitar este caso, debe comprobar regularmente el estado de la licencia; si está en estado de evaluación, llame a esta API nuevamente. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Inicializa una nueva instancia de esta clase.

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Obtiene crédito de consumo

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Decimal | cantidad de consumo |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Obtiene el tamaño del archivo de consumo

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Decimal | cantidad de consumo |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_3}


```
 set_metered_key(public_key, private_key) 
```

Establece la clave pública y privada con licencia medida.<br/>            Si compra una licencia medida, al iniciar la aplicación, debe llamarse a esta API; normalmente, eso es suficiente. <br/>            Sin embargo, si siempre falla la carga de los datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación, <br/>            para evitar este caso, debe comprobar regularmente el estado de la licencia; si está en estado de evaluación, llame a esta API nuevamente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| public_key | string | clave pública |
| private_key | string | clave privada |


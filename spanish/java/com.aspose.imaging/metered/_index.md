---
title: "Medido"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Proporciona métodos medidos para la integración"
type: docs
weight: 74
url: /es/java/com.aspose.imaging/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Proporciona métodos medidos para la integración

En este ejemplo, se intentará establecer la clave pública y privada medida.

`// the component jar file: Metered metered = new Metered(); metered.setMeteredKey("PublicKey", "PrivateKey"); `
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Metered()](#Metered--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Obtiene el tamaño del archivo de consumo |
| [getConsumptionCredit()](#getConsumptionCredit--) | Obtiene el crédito de consumo |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Establece la clave pública y privada medida. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el Object especificado es igual a esta instancia. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Obtiene el tamaño del archivo de consumo

**Returns:**
java.math.BigDecimal - tamaño del archivo de consumo
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Obtiene el crédito de consumo

**Returns:**
java.math.BigDecimal - cantidad de consumo
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Establece la clave pública y privada medida.

Si adquiere una licencia medida, al iniciar la aplicación, debe llamarse a esta API; normalmente, eso es suficiente. Sin embargo, si siempre falla la carga de los datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar este caso, debe comprobar regularmente el estado de la licencia y, si está en estado de evaluación, llamar a esta API nuevamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicKey | java.lang.String | clave pública |
| privateKey | java.lang.String | clave privada |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el Object especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El Object a comparar con esta instancia. |

**Returns:**
boolean - `true` si el Object especificado es igual a esta instancia; de lo contrario, `false`.

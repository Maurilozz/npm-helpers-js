# Bienvenido a helpers reco

Helpers reco es una recopilación de funciones javascript que te serán útiles en diferentes proyectos

# Archivos

index.js

## Funciones

A continuación veras la funciones que contiene este paquete

| Nombre                             | Código              | Parametros                                                                                              |
| ---------------------------------- | ------------------- | ------------------------------------------------------------------------------------------------------- |
| Generar id aleatorio               | `generateId()`      | no necesario                                                                                            |
| Formatear fecha _(largo)_          | `dateFormat()`      | requiere Date.now()                                                                                     |
| Formatear fecha _(numérico)_       | `dateShort()`       | requiere Date.now()                                                                                     |
| Formatear hora _(12hrs)_           | `getTimeFormat()`   | requiere hora 24hrs ejemplo: 14:30                                                                      |
| Formatear numero a precio          | `currencyFormat()`  | requiere valor numérico                                                                                 |
| dirigir scroll suave a un elemento | `animateScroll()`   | requiere valor un id y definir false como segundo argumento si deseas el scroll para otros dispositivos |
| Color de porcentaje                | `percentageMeter()` | requiere un valor numérico                                                                              |
| Seleccionador aleatorio            | `randomElement()`   | requiere un array con datos                                                                             |
| formateador para api de whastapp   | `textWaFormat()`    | requiere un string de texto                                                                             |

## Uso

**textWaFormat**
textWaFormat retornara un string con los simbolos adecuados para la api de whastapp
| Símbolo | Sintaxis| Resultado| Función |
|-----------------|--------|-------------|-|
| (espacio vacio) | `"Hola Mundo"` | `"Hola%20Mundo"`| espacio
| < | `"Hola<Mundo"` | `"Hola%0AMundo"`| Salto de linea
| # | `"Hola#Mundo#"` | ` "Hola```Mundo```" `| Monoespaciado

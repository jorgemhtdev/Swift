# Cadenas y caracteres

**raw strings**: Las cadenas sin formato en Swift 5 nos permiten escribir cadenas de texto en un lenguaje más natural indicada por los símbolos de almohadilla inicial y final (#) antes y después de las comillas.

```swift
let json = "[{\"name\":\"jorge\",\"username\":\"jorgemhtdev\",\"points\":50}]"

let json = #""[{name:jorge,username:jorgemhtdev,points:50}]""#

let username = "jorgemhtdev"

let msg = #"Hola, \#(username)!"#

let message = #"Probando un salto de línea ... \n Hoy es 1976\\04\\1!"#

let message = #"Probando un salto de línea ... \#n ... Hoy es 1976\04\1!"#

```

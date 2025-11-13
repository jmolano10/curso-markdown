# Código

Ya que *Markdown* es utilizado precisamente en el ambiente del desarrollo de software para documentar muchas veces, como se ve en ejercicios pasados tiene también la posibilidad de poder mostrar pedazos de código de manera que estos resalten.

Primero tenemos el código en linea, es es cuando en medio de un texto debemos de poner algún pedazo de código, por lo general es para dar explicaciones sobre el mismo, por ejemplo si estuviéramos hablando de de la creación de párrafos en lenguaje **HMTL** en un párrafo que explicara como se crean, necesitaríamos hablar de la etiqueta `<p>`, aquí se puede apreciar que se le da una apariencia especial al segmento de código dentro del párrafo, para hacer esto se debe encerrar el código que se quiera resaltar con el acento invertido \(\`\). A continuación mostrare como se ve este párrafo en su forma de código.

~~~
Primero tenemos el código en linea, es es cuando en medio de un texto debemos de poner algún pedazo de código, por lo general es para dar explicaciones sobre el mismo, por ejemplo si estuviéramos hablando de de la creación de párrafos en lenguaje **HMTL** en un párrafo que explicara como se crean, necesitaríamos hablar de la etiqueta `<p>`, aquí se puede apreciar que se le da una apariencia especial al segmento de código dentro del párrafo, para hacer esto se debe encerrar el código que se quiera resaltar con el acento invertido \(\`\). A continuación mostrare como se ve este párrafo en su forma de código.
~~~

Ahora para mostrar pedazos grandes de código como el que se monstruo antes, se debe abrir primero un triple acento invertido o triple virgulilla \(~\), escribir el código y luego cerrarlo con el mismo tipo de carácter que se uso. Veamos como se vería una vez más el párrafo anterior, solo que ahora incluiremos los caracteres que formaron el bloque de código. 

```
~~~
Primero tenemos el código en linea, es es cuando en medio de un texto debemos de poner algún pedazo de código, por lo general es para dar explicaciones sobre el mismo, por ejemplo si estuviéramos hablando de de la creación de párrafos en lenguaje **HMTL** en un párrafo que explicara como se crean, necesitaríamos hablar de la etiqueta `<p>`, aquí se puede apreciar que se le da una apariencia especial al segmento de código dentro del párrafo, para hacer esto se debe encerrar el código que se quiera resaltar con el acento invertido \(\`\). A continuación mostrare como se ve este párrafo en su forma de código.
~~~
```
# Prueba de documentación de código

Este es un ejemplo de la prueba de código para JSON

````
{
    "StatusInfo": {
        "Status": "Success",
        "ValueDate": "2024-09-17",
        "DateTime": "2024-09-17T17:34:11",
        "GlobalId": "8ec50eec-ac69-464d-aaeb-d8b07dd42fd5"
    },
    "RatesInfo": [
        {
            "Org": "340",
            "Logo": "515",
            "Pct": "801",
            "InterestRate": "40.00",
            "UpdateDateInterestRate": "2024-11-08T15:00:00"  
        }

    ]
}
````
Continuamos con la descripción del documento. 

En JAVA el metodo que inicia una aplicacón es el método `main`y se ve así. 
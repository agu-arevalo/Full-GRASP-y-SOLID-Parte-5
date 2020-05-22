# PII Full GRASP and SOLID
## FIT
### Universidad Católica del Uruguay

En este programa trabajaremos con recetas de cocina que involucran ingredientes y equipamiento.

## Desafío(s)

Descarguen el archivo adjunto, es el ejemplo de recetas que hemos usado antes; el ejemplo es el mismo, el código tiene modificaciones resultantes de aplicar los principio y patrones anteriores.

La clases que implementan IPrinter, como ConsolePrinter, dependen de la clase Recipe: un mensaje string GetTextToPrint() es enviado a una instancia de Recipe en el método void PrintRecipe(Recipe).

➡️ **Apliquen el principio de inversión de dependencia para que la clase ConsolePrinter no dependa de la clase Recipe.**
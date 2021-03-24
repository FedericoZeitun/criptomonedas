# ¿En qué consiste la aplicación?
Es un cotizador de criptomonedas, donde primero elegimos la moneda dentro de las opciones, y luego elegimos la criptomoneda dentro de las 10 opciones que nos brinda la página.
Al calcular el valor de la criptomoneda en la moneda real elegida, se nos retornará el precio actual en dicha moneda, el valor mas alto, el mas bajo, y la última actualización.

# ¿Cómo fue creado?
El proyecto fue creado utilizando React, con sus respectivos Hooks tradicionales, pero además se optó por crear Custom Hooks. En cuanto al diseño, se utilizó CSS puro para algunas partes, pero en otras se usaron Styled Components. También se importó una librería que permite crear Spinners predeterminados antes que la página arroje el resultado. Para poder
convertir la Criptomoneda en Moneda real, se llamó a la API de "Cryptocompare", utilizando axios en vez de la API Fetch tradicional.

# Link del deployment:
https://affectionate-wescoff-6bc358.netlify.app/

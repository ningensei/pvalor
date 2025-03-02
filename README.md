# Calculadora de p-valor

Esta aplicación web permite calcular el p-valor a partir de un coeficiente de correlación (r) y el número de observaciones (n). Utiliza la fórmula del estadístico t y la distribución t de Student para obtener el p-valor, indicando la 
significancia estadística de la correlación observada.

## Características

- **Entrada de datos:** Permite ingresar el coeficiente de correlación (r) y el número de observaciones (n).
- **Cálculo automático:** Calcula el estadístico t y, a partir de él, el p-valor para una prueba de dos colas.
- **Interfaz amigable:** Usa la librería [Bulma](https://bulma.io/) para un diseño limpio y moderno.
- **Explicación del resultado:** Si el p-valor es extremadamente bajo (menor a 1e-4), se muestra un mensaje explicativo indicando que la correlación es altamente significativa.
- **Tecnología:** Emplea [jStat](https://jstat.github.io/) para los cálculos estadísticos y JavaScript para la lógica.

## Tecnologías utilizadas

- **HTML5 y CSS3**
- **Bulma:** Framework CSS para un diseño responsivo y moderno.
- **JavaScript:** Lógica de cálculo del estadístico t y del p-valor.
- **jStat:** Librería JavaScript para funciones estadísticas.

## Cómo usar

1. Clona o descarga este repositorio en tu máquina local.
2. Abre el archivo `index.html` en tu navegador web.
3. Ingresa el valor del coeficiente de correlación (r) y el número de observaciones (n) en los campos correspondientes.
4. Haz clic en el botón **"Calcular p-valor"** para ver el resultado.
5. Si el p-valor es extremadamente bajo, se mostrará una notificación explicativa adicional.

## Ejemplo

Si ingresas:
- **r:** 0.999
- **n:** 50

El resultado será un p-valor muy cercano a 0 (mostrado como `0.0000e+0`), lo que indica que la correlación es estadísticamente significativa y que es extremadamente improbable que se haya obtenido por azar.


## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes alguna sugerencia o encuentras algún error, por favor abre un _issue_ o envía un _pull request_.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Créditos

- [Bulma](https://bulma.io/) - Framework CSS.
- [jStat](https://jstat.github.io/) - Librería JavaScript para cálculos estadísticos.



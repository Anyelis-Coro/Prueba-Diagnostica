# Evaluador de Expresiones Aritméticas con Notación Científica

Este programa permite evaluar expresiones aritméticas con los operadores básicos (+, -, *, /) y números en notación científica (por ejemplo, `5E-8`, `125E25`).

# Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (puro / Vanilla JS)


# Estructura del Proyecto
```
Programa 3/
├── prog3.html       # Archivo principal con interfaz y lógica
├── README.md        # Documentación del programa
```

# Ejemplo de expresión válida

```
(125E10 - 1e15)/5E-85*15
```


# Cómo usar

1. Abre `prog3.html` en tu navegador.
2. Introduce una expresión matemática válida.
3. Presiona el botón "Evaluar".
4. Verás el resultado debajo del formulario.

#  Notas

- Este programa utiliza `eval()` de JavaScript, que ya reconoce notación científica como `1e6`.
- Se reemplaza la `E` por `e` en la expresión para garantizar compatibilidad con la función `eval()` de JavaScript.

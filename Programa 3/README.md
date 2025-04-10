# Evaluador de Expresiones Aritméticas con Notación Científica

Este programa permite evaluar expresiones aritméticas con los operadores básicos (+, -, *, /) y números en notación científica (por ejemplo, `5E-8`, `125E25`).

# Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (puro / Vanilla JS)


# Estructura de la carpeta
```
Programa 3/
├── prog3.html       # Archivo principal con interfaz y lógica
├── README.md        # Documentación del programa
```

# Ejemplo de expresión válida

```
(125E10 - 1e15)/5E-85*15
```

# Cómo ejecutar el programa

 1. Descarga o clona este repositorio:
   ```bash
   git clone https://github.com/Anyelis-Coro/Prueba-Diagnostica.git
   cd Programa 3
   ```
2. Abre `prog3.html` en el navegador.
3. Introduce una expresión matemática válida.
4. Presiona el botón "Evaluar".
5. Verás el resultado debajo del formulario.

#  Notas

- Este programa utiliza `eval()` de JavaScript, que ya reconoce notación científica como `1e6`.
- Se reemplaza la `E` por `e` en la expresión para garantizar compatibilidad con la función `eval()` de JavaScript.

# Autor

- Desarrollado por Anyelis Coro


# Contador de Palabras en una Cadena

Este programa permite ingresar una cadena de texto y una palabra para contar cuántas veces aparece dicha palabra dentro del texto.

# Características

- Interfaz web simple.
- Cuenta palabras respetando límites (no cuenta partes dentro de otras palabras).
- No distingue entre mayúsculas y minúsculas.

# Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (puro / Vanilla JS)

---

# Estructura del Proyecto

```
Programa 1/
├── prog1.html       # Archivo principal con interfaz y lógica
├── README.md        # Documentación del programa
```

# Cómo usar

1. Abre el archivo `prog4.html` en tu navegador.
2. Escribe un texto en el área "Cadena C".
3. Escribe la palabra que deseas buscar.
4. Haz clic en el botón **"Contar ocurrencias"**.
5. Se mostrará el número de veces que aparece la palabra.

# Ejemplo

Texto: `JavaScript es divertido. Amo JavaScript.`  
Palabra: `javascript`  
Resultado: `2 ocurrencias`

# Notas

- Usa expresiones regulares para hacer la búsqueda.
- Se considera coincidencia solo si es una palabra completa (`\bpalabra\b`).

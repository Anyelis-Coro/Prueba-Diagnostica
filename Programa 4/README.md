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

# Estructura de la carpeta

```
Programa 4/
├── prog4.html       # Archivo principal con interfaz y lógica
├── README.md        # Documentación del programa
```

 # Cómo ejecutar el programa

 1. Descarga o clona este repositorio:
   ```bash
   git clone https://github.com/Anyelis-Coro/Prueba-Diagnostica.git
   cd Programa 4
   ```
2. Abre el archivo `prog4.html` en el navegador.
3. Escribe un texto en el área "Cadena C".
4. Escribe la palabra que deseas buscar.
5. Haz clic en el botón **"Contar ocurrencias"**.
6. Se mostrará el número de veces que aparece la palabra.

# Ejemplo

Texto: `JavaScript es divertido. Amo JavaScript.`  
Palabra: `javascript`  
Resultado: `2 ocurrencias`

# Notas

- Usa expresiones regulares para hacer la búsqueda.
- Se considera coincidencia solo si es una palabra completa (`\bpalabra\b`).

# Autor

- Desarrollado por Anyelis Coro

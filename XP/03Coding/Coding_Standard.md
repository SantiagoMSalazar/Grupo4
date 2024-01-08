<h1 align="center">
    Escuela Politécnica Nacional<br>
    Facultad de Ingeniería en Sistemas<br>
    Metodologías Ágiles<br>
</h1>

# Estándares de Codificación - Empresa Yoghismo
Enlace: https://epnecuador-my.sharepoint.com/personal/santiago_salazar_epn_edu_ec/_layouts/15/stream.aspx?id=%2Fpersonal%2Fsantiago%5Fsalazar%5Fepn%5Fedu%5Fec%2FDocuments%2FGrabaciones%2FVideo%2DGrupo4%2D20240107%5F190530%2DGrabaci%C3%B3n%20de%20la%20reuni%C3%B3n%2Emp4&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview
## Convenciones Generales

1. **Indentación:**
   - Utilizar tabulaciones en lugar de espacios.
   - Establecer una indentación de 1 tabulación.

2. **Punto y Coma:**
   - Incluir punto y coma al final de cada declaración.

3. **Longitud de línea:**
   - Limitar la longitud de línea a 80-100 caracteres.

4. **Espacios en Blanco:**
   - Utilizar espacios en blanco de manera consistente para mejorar la legibilidad.

## Nombrado de Variables

5. **Variables:**
   - Utilizar camelCase para nombrar variables (e.g., `miVariable`).

6. **Constantes:**
   - Nombrar constantes en mayúsculas con guiones bajos para separar palabras (e.g., `MI_CONSTANTE`).

## Estructuras de Control

7. **if-else:**
   - Incluir llaves incluso para bloques de código de una sola línea.
```javascript
if (condicion) {
    // código
} else {
    // código
}
```

8. **Switch:**
   - Incluir un comentario `// fall through` cuando se omite un `break` de manera intencional.

```javascript
switch (variable) {
    case 1:
        // código
        break;
    case 2:
        // código
        // fall through
    case 3:
        // código
        break;
    default:
        // código
        break;
}
```


## Funciones

9. **Declaración de Funciones:**
   - Utilizar la declaración de funciones con nombre en lugar de expresiones de función anónimas.

```javascript
function miFuncion(parametro) {
    // código
}
```


10. **Parámetros de Función:**
   - Utilizar camelCase para los nombres de parámetros.

```javascript
function sumaDosNumeros(numeroUno, numeroDos) {
    return numeroUno + numeroDos;
}
```


## Comentarios

11. **Comentarios:**
   - Utilizar comentarios descriptivos y claros. Evitar comentarios obvios o innecesarios.

```javascript
// Buen comentario
function dividirDosNumeros(dividendo, divisor) {
    // Verificar que el divisor no sea cero antes de realizar la división
    if (divisor !== 0) {
        return dividendo / divisor;
    } else {
        console.error("Error: División por cero.");
        return NaN;
    }
}
```

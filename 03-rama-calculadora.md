# Paso 3: Crear Rama y Añadir Código de la Calculadora

1. Crea una nueva rama:

```bash
git checkout -b calculadora-basica
```

2. Crea un archivo `calculadora.js` con lo siguiente:

```javascript
function sumar(a, b) {
  return a + b;
}

function restar(a, b) {
  return a - b;
}
```

3. Guarda el archivo.

4. Agrega y haz commit:

```bash
git add calculadora.js
git commit -m "Agregar suma y resta a la Calculadora"
git push origin calculadora-basica
```

[Anterior](02-clonar-vscode.md) | [Siguiente: Crear el Pull Request »](04-pull-request-basico.md)

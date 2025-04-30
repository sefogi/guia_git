# Paso 6: Resolver el Issue en Nueva Rama

1. Sincroniza tu repositorio local:

```bash
git checkout main
git pull origin main
```

2. Crea una nueva rama:

```bash
git checkout -b operaciones-extra
```

3. Edita `calculadora.js` y agrega:

```javascript
function multiplicar(a, b) {
  return a * b;
}

function dividir(a, b) {
  if (b === 0) throw new Error("División por cero");
  return a / b;
}
```

4. Guarda, agrega y haz commit:

```bash
git add calculadora.js
git commit -m "Agregar multiplicación y división"
git push origin operaciones-extra
```

5. Crea un Pull Request hacia `main`, asociando el Issue (usa `Closes #N` en la descripción).

6. Acepta el Pull Request. El issue se cerrará automáticamente.

[Anterior](05-crear-issue.md) | [Siguiente: Crear un README detallado »](07-readme-proyecto.md)

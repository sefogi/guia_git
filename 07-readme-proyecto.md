# Paso 7: Crear un README detallado en la rama `main`

1. Crea el archivo `README.md` en la raíz del proyecto con el siguiente contenido:

```markdown
# Calculadora JS

Una calculadora simple implementada en JavaScript que permite realizar operaciones básicas.

## Características

- Operaciones disponibles: `suma`, `resta`, `multiplicación`, `división`
- Código limpio y modular
- Listo para extenderse con interfaz web o CLI

## Instalación

Clona el repositorio:

```bash
git clone https://github.com/tu_usuario/calculadora-js.git
cd calculadora-js
```

## Pruebas rápidas

Edita `index.html` o usa consola del navegador:

```html
<script src="calculadora.js"></script>
<script>
  console.log(sumar(2, 3)); // 5
  console.log(dividir(6, 2)); // 3
</script>
```

## Estructura del Proyecto

```
calculadora-js/
├── calculadora.js
└── README.md
```

## Futuras mejoras

- Agregar interfaz gráfica con HTML/CSS
- Crear pruebas automatizadas con Jest
- Convertir en módulo NPM
```

2. Guarda, agrega y haz push:

```bash
git add README.md
git commit -m "Agregar README detallado del proyecto"
git push origin main
```

[Anterior](06-rama-issue.md) | [Siguiente: Crear una discusión »](08-discusion.md)

# Consigna del Parcial - Detalle de Producto

Este HTML y CSS ya tienen una estructura base armada.
Tu tarea es completar los siguientes puntos en el archivo `parcial.css`:

## 1) Variables CSS

- Pasar TODOS los colores que están "hardcodeados" en el CSS a variables.
- Definirlas en `:root` (ej: `--color-primario`, `--color-fondo`, etc.)
- Reemplazar los valores en el resto del CSS para usar `var(--nombre)`.

## 2) Selectores nth-child

Aplicar selectores `nth-child` a la lista de características (`.feature-list li`):

- Cambiar el color de fondo al primero.
- Agregarle un borde diferente o cambiar el color del texto al último.
- Aplicar un color de fondo distinto a los pares.
- Aplicar un color de fondo distinto a los impares.

## 3) Estados interactivos

- El botón `.btn-primary` debe cambiar de color al pasar el mouse por encima.
- El botón `.btn-secondary` debe tener un efecto al pasar el mouse por encima (cambio de fondo, borde, etc.).
- El input de cantidad `.qty-input` debe tener un estilo distinto al hacer focus.

## 4) Flexbox

- El contenedor `.product-detail` debe mostrar la imagen y la info del producto en fila (lado a lado).
- El `.product-actions` debe alinear los botones y el input de cantidad en fila con espacio entre ellos.
- El navbar (`.navbar`) debe distribuir en horizontal el logo de los `li` items.

## 5) Navbar Responsive (Media Query)

- Ya existe un botón hamburguesa (`.hamburger`) PERO está siempre visible y los links también.
- Ocultar el botón hamburguesa en pantallas grandes.
- En pantallas chicas (`max-width: 768px`):
  - Ocultar los `.nav-links`
  - Mostrar el botón hamburguesa

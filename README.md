# Joyas & Arte — Catálogo Web

Catálogo de joyería con enlace directo a WhatsApp para pedidos.

## Cómo agregar/quitar productos

Abre `index.html` y busca la sección `const productos = [` — ahí editas el array. Cada producto tiene este formato:

```js
{
    id: 1,
    nombre: 'Nombre de la joya',
    precio: '$1,200',
    categoria: 'Anillos',         // Anillos, Collares, Pulseras, Aretes, Dijes, etc.
    imagen: 'img/tu-foto.jpg',    // Ruta de lagit p imagen
    descripcion: 'Breve descripción.'
}
```

## Cómo agregar imágenes

1. Pon tus fotos en la carpeta `img/` (JPG o PNG).
2. En el producto, escribe `imagen: 'img/tu-archivo.jpg'`.

## Cómo subirlo a GitHub Pages (GRATIS)

1. Crea una cuenta en https://github.com
2. Dale clic al botón **+** (arriba a la derecha) → **New repository**
3. Ponle nombre, ej: `joyeria-catalogo`, y créalo (público)
4. Abre la terminal y escribe:

```bash
cd ruta/del/proyecto
git init
git add .
git commit -m "Primer commit"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/joyeria-catalogo.git
git push -u origin main
```

5. Ve a tu repo en GitHub → Settings → Pages
6. En "Source" selecciona `main` y `/ (root)`, da clic en **Save**
7. Espera 1-2 minutos y tu página estará en:

```
https://TU_USUARIO.github.io/joyeria-catalogo
```

Ese link lo pegas en tu estado de WhatsApp.

## Cambiar número de WhatsApp

Busca esta línea en `index.html`:

```js
const WHATSAPP_NUMBER = '526421406065';
```

Cambia el número (código de país + dígitos, sin espacios ni signos).

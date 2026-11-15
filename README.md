# 🥄 Cocina Básica · Recetario

Sitio web estático con las recetas del *Manual de apoyo: Cocina Básica* (Escuela de Gastronomía Duoc UC, enero 2024): salsas madre, sus derivados y la masa para pastas frescas.

## Contenido
- **Portada interactiva** (`index.html`): presentación, tarjetas giratorias con las características y componentes de una salsa, menú por áreas, recetario con filtros y buscador, y un explorador de salsas madre → derivadas.
- **6 áreas** (`areas/`): Salsas frías emulsionadas, Salsas blancas, Salsas oscuras, Salsas semicoaguladas calientes, Salsas emulsionadas calientes, Pastas italianas.
- **11 recetas** (`recetas/`), cada una en su propia página con escalador de porciones, pasos que se marcan como hechos y salsas derivadas.
- **Fotografías** de Wikimedia Commons (licencias libres), enlazadas desde su servidor. Si alguna no carga, se muestra la ilustración de respaldo de `assets/img/recetas/`.

## Créditos de las fotos
- **Mayonesa**: [Fresh mayonnaise.jpg](https://commons.wikimedia.org/wiki/File:Fresh_mayonnaise.jpg) — Jason Terk
- **Vinagreta**: [Raspberry vinaigrette.jpg](https://commons.wikimedia.org/wiki/File:Raspberry_vinaigrette.jpg) — Tricia
- **Velouté**: [Making White sauce 5.jpg](https://commons.wikimedia.org/wiki/File:Making_White_sauce_5.jpg) — Roozitaa
- **Bechamel**: [2021 Sos beszamelowy.jpg](https://commons.wikimedia.org/wiki/File:2021_Sos_beszamelowy.jpg) — Jacek Halicki
- **Salsa por reducción de crema**: [Cream sauce.jpg](https://commons.wikimedia.org/wiki/File:Cream_sauce.jpg)
- **Salsa española**: [Sauce Spagnole-09.JPG](https://commons.wikimedia.org/wiki/File:Sauce_Spagnole-09.JPG) — Tamorlan
- **Salsa holandesa**: [Spargel sauce hollandaise.jpg](https://commons.wikimedia.org/wiki/File:Spargel_sauce_hollandaise.jpg) — Elya
- **Salsa bearnesa**: [Béarnaise sauce with Tarragon garnish.jpeg](https://commons.wikimedia.org/wiki/File:B%C3%A9arnaise_sauce_with_Tarragon_garnish.jpeg) — Alexander Guy
- **Beurre blanc**: [Purple asparagus in Beurre blanc sauce.jpg](https://commons.wikimedia.org/wiki/File:Purple_asparagus_in_Beurre_blanc_sauce.jpg) — stu_spivack
- **Beurre fondue**: [Bowl of melted butter.jpg](https://commons.wikimedia.org/wiki/File:Bowl_of_melted_butter.jpg)
- **Masa para pastas frescas**: [The Art of Pasta Making in Italy with Mama Isa.jpg](https://commons.wikimedia.org/wiki/File:The_Art_of_Pasta_Making_in_Italy_with_Mama_Isa.jpg) — Isacookinpadua

Para usar tus propias fotos, cambia en los archivos HTML las URLs de Wikimedia por tus archivos (por ejemplo `assets/img/fotos/mayonesa.jpg`).

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `cocina-basica`).
2. Sube **el contenido de esta carpeta** a la raíz del repositorio (botón *Add file → Upload files*, o con git):
   ```bash
   git init
   git add .
   git commit -m "Recetario Cocina Básica"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/cocina-basica.git
   git push -u origin main
   ```
3. En el repositorio ve a **Settings → Pages**, en *Source* elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
4. En uno o dos minutos el sitio estará en `https://TU-USUARIO.github.io/cocina-basica/`.

## Editar
Es HTML, CSS y JavaScript puro, sin dependencias. Los estilos están en `assets/css/styles.css` y las interacciones en `assets/js/main.js`.

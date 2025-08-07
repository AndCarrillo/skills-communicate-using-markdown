# Guía Completa de Markdown - Referencia Rápida

📚 **Guía de referencia para consultar en cualquier momento**

Esta guía contiene todos los elementos de Markdown aprendidos en el ejercicio "Communicate using Markdown" con ejemplos prácticos y enlaces útiles.

> 💝 **Esta guía está basada en el ejercicio práctico completado [Communicate using Markdown](https://github.com/skills/communicate-using-markdown) de GitHub Skills**

---

## 📖 Índice

1. [¿Qué es Markdown?](#qué-es-markdown)
2. [Encabezados](#encabezados)
3. [Listas](#listas)
4. [Bloques de Código](#bloques-de-código)
5. [Imágenes](#imágenes)
6. [Enlaces Útiles](#enlaces-útiles)
7. [Consejos Adicionales](#consejos-adicionales)

---

## ¿Qué es Markdown?

Markdown es una sintaxis ligera para comunicarse en GitHub. Puede formatear texto para agregar encabezados, listas, negritas, cursivas, tablas y muchos otros estilos.

**Puede usar Markdown en:**

- Comentarios en issues, pull requests y discusiones
- Archivos con extensión `.md` o `.markdown`
- Fragmentos de texto en Gists
- README de repositorios

📋 **Enlaces de referencia:**

- [GitHub Blog](https://github.blog/) - Ideas y temas
- [GitHub Pages](https://skills.github.com/#first-day-on-github) - Publicar sitios web
- [Documentación oficial de Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

---

## Encabezados

Los encabezados son texto más grande al comienzo de una sección. Hay seis tamaños disponibles.

### Sintaxis:

```markdown
# Esto es un encabezado `<h1>`, el más grande

## Esto es un encabezado `<h2>`

### Esto es un encabezado `<h3>`

#### Esto es un encabezado `<h4>`

##### Esto es un encabezado `<h5>`

###### Esto es un encabezado `<h6>`, el más pequeño
```

### Resultado:

# Esto es un encabezado `<h1>`, el más grande

## Esto es un encabezado `<h2>`

### Esto es un encabezado `<h3>`

#### Esto es un encabezado `<h4>`

##### Esto es un encabezado `<h5>`

###### Esto es un encabezado `<h6>`, el más pequeño

---

## Listas

Markdown soporta 3 tipos de listas comunes:

### 1. Lista No Ordenada (con viñetas)

```markdown
- Elemento 1
- Elemento 2
- Elemento 3
```

**Resultado:**

- Elemento 1
- Elemento 2
- Elemento 3

### 2. Lista Ordenada (numerada)

```markdown
1. Paso 1
1. Paso 2
1. Paso 3
```

**Resultado:**

1. Paso 1
2. Paso 2
3. Paso 3

### 3. Lista de Tareas (con checkboxes)

```markdown
- [x] Esta tarea está completa
- [ ] Esta tarea no está completa
- [ ] Otra tarea pendiente
```

**Resultado:**

- [x] Esta tarea está completa
- [ ] Esta tarea no está completa
- [ ] Otra tarea pendiente

**💡 Consejo:** Los issues y pull requests pueden usar la sintaxis de tareas para mostrar progreso.

---

## Bloques de Código

### Código en línea

```markdown
Usa `backticks` para código en línea
```

**Resultado:** Usa `backticks` para código en línea

### Bloques de código con sintaxis específica

#### Comando de Terminal:

````markdown
```bash
git clone https://github.com/skills/communicate-using-markdown
```
````

````

**Resultado:**
```bash
git clone https://github.com/skills/communicate-using-markdown
````

#### Código JavaScript:

````markdown
```js
var myVar = "Hello, world!";
console.log(myVar);
```
````

````

**Resultado:**
```js
var myVar = "Hello, world!";
console.log(myVar);
````

#### Ejemplo práctico (ffmpeg):

````markdown
```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
````

````

**Resultado:**
```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
````

**💡 Consejo:** Muchos lenguajes de programación son compatibles. ¡Prueba con diferentes extensiones!

---

## Imágenes

### Markdown Simple

```markdown
![Texto alternativo](ruta/a/imagen.png)
![Mona the Octocat](https://octodex.github.com/images/original.png)
```

### HTML para mayor control

```html
<img
  alt="Descripción"
  src="https://octodex.github.com/images/original.png"
  width="200"
  align="right"
/>
```

**Ventajas del HTML:**

- Control del tamaño (`width` y `height`)
- Posicionamiento (`align="left|right|center"`)
- Mayor flexibilidad

### Ejemplo práctico:

```html
<img
  alt="Cloudy morning"
  src="https://octodex.github.com/images/cloud.jpg"
  width="100"
  align="right"
/>
```

---

## Enlaces Útiles

### 🔗 Recursos de GitHub

- [GitHub Blog](https://github.blog/) - Para ideas de temas
- [GitHub Pages](https://skills.github.com/#first-day-on-github) - Crear sitios web
- [GitHub Explore](https://github.com/explore) - Encontrar proyectos
- [GitHub Docs](https://docs.github.com/en/get-started) - Documentación oficial

### 🛠️ Herramientas

- [ffmpeg](https://www.ffmpeg.org) - Procesamiento de video y audio
- [GitHub Skills](https://skills.github.com/) - Más ejercicios interactivos

### 📚 Aprendizaje

- [Markdown Guide](https://www.markdownguide.org/) - Guía completa de Markdown
- [GitHub Flavored Markdown](https://github.github.com/gfm/) - Especificaciones de GitHub

---

## Consejos Adicionales

### ✅ Buenas Prácticas

1. **Usa la pestaña Preview** para verificar el formato antes de hacer commit
2. **Organiza el contenido** con encabezados claros y jerarquía lógica
3. **Incluye texto alternativo** en las imágenes para accesibilidad
4. **Usa listas de tareas** para trackear progreso en issues y PRs

### 🚀 Workflow Recomendado

1. Crear una nueva rama (`git checkout -b nombre-rama`)
2. Crear/editar archivo `.md`
3. Usar Preview para revisar formato
4. Hacer commit de los cambios
5. Crear Pull Request
6. Mergear a la rama principal

### 📝 Ejemplo de Estructura de Blog Post

````markdown
# Título del Post

<img alt="Imagen descriptiva" src="url-imagen.jpg" width="100" align="right">

## Planificación Matutina

- [ ] Revisar el [GitHub blog](https://github.blog/) para ideas
- [ ] Aprender sobre [GitHub Pages](https://skills.github.com/#first-day-on-github)
- [ ] Convertir mi primer post en una página web

## Revisión

Convertir imagen de modo oscuro a modo claro usando [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
````

---

## 🎉 ¡Completado!

Lo aprendido:

- ✅ Agregar encabezados para organizar contenido
- ✅ Crear listas de tareas para planificar
- ✅ Guardar fragmentos de código para uso futuro
- ✅ Agregar imágenes para mejorar la presentación
- ✅ Crear posts completos usando sintaxis Markdown

**Próximos pasos:**

- Toma otro ejercicio de GitHub Skills
- Continúa con el ejercicio de GitHub Pages
- Aprende más sobre Markdown avanzado
- Contribuye a proyectos open source

---

_📅 Creado: Agosto 2025 | 🔄 Última actualización: Agosto 6, 2025_

# PC EXTREME

Landing page responsive para la venta de computadoras personalizadas para hogar, oficina y gaming.

## 🌐 Sitio desplegado

GitHub Pages:

https://andrepr16.github.io/tienda-computadoras/

---

## 📂 Páginas del proyecto

- Inicio (`index.html`)
- Planes y precios (`precios.html`)
- Preguntas frecuentes (`faq.html`)

---

## 🎨 Tokens CSS

| Token | Valor | Uso |
|---------|------|------|
| --color-primary | #1a1a1a | Botones y elementos principales |
| --color-accent | #ff4500 | Hover del menú y acentos |
| --color-text | #1a1a1a | Texto principal |
| --color-bg | #ffffff | Fondo principal |
| --color-bg-soft | #f5f5f5 | Cards, footer y fondos secundarios |
| --color-border | #e0e0e0 | Bordes |
| --font-text | system-ui, -apple-system, sans-serif | Tipografía principal |
| --font-size | 16px | Texto base |
| --font-size-title | 28px | Títulos y precios |
| --space-sm | 8px | Espaciado pequeño |
| --space-md | 16px | Espaciado mediano |
| --space-lg | 32px | Espaciado grande |
| --radius | 8px | Bordes redondeados |
| --shadow-sm | 0 1px 3px rgba(0,0,0,.08) | Sombra normal |
| --shadow-md | 0 4px 12px rgba(0,0,0,.12) | Sombra en hover |
| --transition-speed | .3s | Velocidad de transición |

---

## ✅ Validaciones implementadas

| Campo | Validación | Descripción |
|---------|---------|---------|
| Nombre | `required` + `minlength="3"` | Debe tener al menos 3 caracteres |
| Correo electrónico | `type="email"` + `required` | Debe tener formato válido |
| Teléfono | `type="tel"` + `pattern="[0-9]{9}"` | Debe contener exactamente 9 dígitos |
| Motivo | `<select>` + `required` | Obliga a seleccionar una opción |
| Mensaje | `required` + `minlength="10"` | Debe contener al menos 10 caracteres |
| Términos y condiciones | `checkbox` + `required` | Es obligatorio aceptarlos |

---

## 🛠 Tecnologías utilizadas

- HTML5
- CSS3
- Flexbox
- CSS Grid
- Media Queries
- CSS Variables
- Git
- GitHub
- GitHub Pages

---

## 🌳 Flujo Git utilizado

### Crear rama

```bash
git checkout -b feature/form-validado
```

### Commit

```bash
git commit -m "feat: agrega validacion nativa al formulario de contacto"
```

### Push

```bash
git push -u origin feature/form-validado
```

### Pull Request y Merge

Los cambios fueron integrados a `main` mediante un Pull Request en GitHub.

### Sincronización local

```bash
git checkout main
git pull
```

---

## 👨‍💻 Autor

**Johnn Peña Rivera**

Proyecto desarrollado para el Módulo 1 - Laboratorio 04: CSS Variables + Forms Validados + Git Workflow.
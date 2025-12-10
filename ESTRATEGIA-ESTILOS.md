# 🎨 Estrategia para Aplicar Estilos

## 📋 Metodología

### 1. **Usar Variables CSS** (ya creadas)
```css
--space-xs: 16px
--space-sm: 24px
--space-md: 32px
--space-lg: 80px
--space-xl: 120px
--space-xxl: 144px
--max-width: 940px
```

### 2. **Trabajar por Secciones**
- ✅ Home Page (index.html)
- ✅ Projects Page (projects.html)
- ✅ Project Detail Pages (ivydecarb.html, mscope.html, etc.)

### 3. **Clases Reutilizables Disponibles**
- `.container` - Contenedor principal
- `.btn`, `.btn-sm`, `.btn-md` - Botones
- `.card`, `.card-link`, `.card-image` - Cards
- `.section-hero`, `.section-projects` - Secciones
- `.heading-hero`, `.section-title` - Headings

### 4. **Flujo de Trabajo**
1. Abrir `http://localhost:4173/index.html` en el navegador
2. Editar `css/portfolio.css`
3. Guardar y recargar el navegador (F5)
4. Ver cambios en tiempo real

## 🎯 Prioridades

### Home Page (index.html)
- [ ] Alinear heading y botón a la izquierda
- [ ] Ajustar espaciado entre secciones
- [ ] Cards con mismo alto
- [ ] Border radius en cards
- [ ] Footer CTA alineado

### Projects Page (projects.html)
- [ ] Todo alineado a la izquierda
- [ ] Cards con mismo alto
- [ ] Espaciado consistente

### Project Detail Pages
- [ ] Espaciado de imágenes (144px)
- [ ] Columnas (4 columnas, 3 columnas)
- [ ] Alineación de textos
- [ ] Cards rectangulares

## 💡 Tips

1. **Siempre usar variables**: `padding: var(--space-sm)` en vez de `padding: 24px`
2. **Crear clases nuevas** cuando algo se repite 2+ veces
3. **Usar selectores específicos** para páginas: `.index-page .section-hero`
4. **Probar responsive** después de cada cambio importante





# 🌿 ENVAK — Landing Page Corporativa

Landing page moderna, responsiva y de alta conversión para **ENVAK S.A.C.**, empresa especializada en **Gestión Ambiental Responsable**, recolección, transporte, valorización y disposición final de residuos sólidos en Lima, Perú.

---

## 📸 Vista General y Características

- **Diseño Fiel a la Identidad de Marca:** Basado en la paleta corporativa verde bosque (`#14532B`), verde lima/hoja (`#4ADE80`), fondos claros y contrastes oscuros.
- **Logotipos e Iconografía Oficiales:**
  - Header con logotipo original transparente de ENVAK.
  - Footer con versión monocromática en blanco sobre fondo verde oscuro.
  - Favicon e insignias con el isotipo oficial de la hoja.
- **Fotografía Real Integrada:**
  - Hero con el operario en uniforme oficial y camión recolector ENVAK.
  - Insignia flotante animada: *"Juntos por un planeta más limpio"*.
  - Banner social proof con el camión en ruta y clientes corporativos (Alicorp, Backus, Coca-Cola, Nestlé, UNACEM, Ransa).
  - Banner de impacto ambiental con brote en tierra fértil (*"Un pequeño gesto hace una gran diferencia"*).
- **Formulario de Cotización Interactivo:**
  - Validación de campos requeridos en tiempo real.
  - Contador dinámico de caracteres en el mensaje (`0/500`).
  - Animación de confeti festivo y modal de confirmación con **SweetAlert2**.
  - Opción de redirección automática con datos estructurados directo a **WhatsApp**.
- **Canales de Atención Directos:**
  - 📱 **WhatsApp:** `+51 904 376 366`
  - ✉️ **Correo:** `contacto@envak.com`
  - 📍 **Ubicación:** Lima, Perú
- **100% Responsivo:** Adaptado para teléfonos móviles, tablets y pantallas de escritorio (incluye menú hamburguesa para dispositivos táctiles).

---

## 📁 Estructura del Proyecto

```text
envak/
├── index.html              # Archivo principal de la landing page (HTML5 + Tailwind)
├── README.md               # Documentación del proyecto
└── assets/                 # Recursos gráficos optimizados
    ├── logo.png            # Logotipo oficial ENVAK (fondo transparente)
    ├── logo-white.png      # Logotipo oficial versión blanca (para footer)
    ├── icon.png            # Isotipo oficial circular con hoja
    ├── favicon.png         # Icono para la pestaña del navegador (64x64)
    ├── hero-worker-hq.jpg  # Fotografía del operario y camión ENVAK (Hero)
    ├── envak-truck-hq.jpg  # Fotografía del camión en ruta (Social Proof)
    └── sprout-plant-hq.jpg # Fotografía del brote de planta (Banner inferior)
```

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Descripción |
|---|---|
| **HTML5 semántico** | Estructura optimizada para accesibilidad y SEO |
| **Tailwind CSS (CDN)** | Estilos utilitarios rápidos y responsive sin necesidad de compilación |
| **Lucide Icons** | Iconografía SVG moderna y minimalista |
| **SweetAlert2** | Modales de confirmación interactivos y elegantes |
| **Canvas Confetti** | Efecto de celebración visual al enviar el formulario |
| **Google Fonts** | Tipografías *Inter* (sans-serif corporativa) y *Caveat* (cursiva orgánica) |

---

## 🚀 Cómo Ejecutar el Proyecto

No requiere instalación previa de Node.js ni paquetes adicionales. Funciona de inmediato:

### Opción 1: Apertura directa
1. Ve a la carpeta `envak/`.
2. Haz doble clic en el archivo **`index.html`** para abrirlo en tu navegador favorito (Chrome, Edge, Firefox, etc.).

### Opción 2: Con Live Server (Recomendado en VS Code)
1. Abre la carpeta `envak` en **Visual Studio Code**.
2. Haz clic derecho sobre `index.html` y selecciona **"Open with Live Server"**.

### Opción 3: Con servidor local de Python
Si deseas probarlo desde terminal:
```bash
# Dentro de la carpeta envak:
python -m http.server 8000
```
Luego abre tu navegador en `http://localhost:8000`.

---

## ⚙️ Personalización Rápida

- **Cambiar número de WhatsApp:** Busca el número `904376366` en `index.html` y reemplázalo por el nuevo número con código de país (ej. `519XXXXXXXX`).
- **Cambiar correo electrónico:** Busca `contacto@envak.com` y modifícalo en los enlaces `mailto:`.
- **Modificar textos o servicios:** Todos los textos están claramente delimitados por comentarios semánticos en `index.html` (`HEADER`, `HERO`, `BENEFICIOS`, etc.).

---

## 📄 Derechos y Licencia

© 2025 **ENVAK S.A.C.** Todos los derechos reservados.  
*Gestión ambiental responsable, hoy y siempre.* 🍃

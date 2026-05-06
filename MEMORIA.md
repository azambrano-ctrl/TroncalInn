# TroncalInn – Memoria del Proyecto

## 🌐 Sitio Web
- **Producción:** https://tourmaline-mooncake-3b28c1.netlify.app
- **Repositorio:** https://github.com/azambrano-ctrl/TroncalInn

## 🔐 Credenciales Admin
- **URL admin:** `/login.html`
- **Usuario:** `admin`
- **Contraseña:** `TroncalInn2026`
- **Acceso secreto:** 5 clics en el logo del footer → redirige a login

## 📁 Estructura de Archivos
```
TroncalInn/
├── index.html       → Sitio web principal
├── admin.html       → Panel de administración (CMS)
├── login.html       → Login del admin
├── MEMORIA.md       → Este archivo
└── images/
    ├── LOGO.png
    ├── hab-individual.webp
    ├── hab-matrimonial.jpg
    ├── hab-doble.webp
    ├── hab-triple.jpg
    └── hab-cuadruple.webp
```

## 🏨 Datos del Hotel
- **Nombre:** TroncalInn Hotel
- **Dirección:** Av. 25 de Agosto y 12va Este, La Troncal, Cañar – Ecuador
- **Coordenadas:** Lat -2.432483 / Lon -79.334175

## 🛏️ Habitaciones y Precios
| Habitación | Precio/noche |
|---|---|
| Individual | $25 |
| Matrimonial | $30 |
| Doble | $35 |
| Triple | $50 |
| Cuádruple | $65 |

## ⚙️ Stack Técnico
- HTML + CSS + JS puro (sin framework)
- **GSAP + ScrollTrigger** → galería horizontal y parallax hero
- **AOS** → animaciones al hacer scroll
- **Leaflet.js** → mapa satélite con pin del hotel
- **Font Awesome 6.5** → iconos sociales
- **localStorage** → almacena datos del admin (contenido editable)
- **sessionStorage** → autenticación del admin
- **Python HTTP Server** → servidor local (`python -m http.server 3000`)

## 🗺️ Mapa
- Librería: Leaflet.js v1.9.4
- Tiles satélite: Esri World Imagery
- Tiles etiquetas: CartoDB Voyager Labels
- Coordenadas fijas: `-2.432483, -79.334175`

## 📡 Deploy
- Plataforma: **Netlify** (cuenta HOTEL)
- CLI instalada: `netlify-cli`
- Sitio vinculado: `tourmaline-mooncake-3b28c1`
- Comando para publicar cambios:
```bash
netlify deploy --prod --dir "C:\Users\ROAIMA\Downloads\TroncalInn"
```

## 💾 GitHub
- Cuenta: `azambrano-ctrl`
- Repo: `TroncalInn`
- Comandos para guardar cambios:
```bash
git add .
git commit -m "descripción del cambio"
git push
```

## 🔧 Funciones del Panel Admin
- **General:** nombre hotel, logo, teléfono, email, horarios
- **Hero:** imagen fondo, título, subtítulo
- **Habitaciones:** nombre, descripción, precio, foto, características
- **Galería:** fotos con descripción
- **Amenidades:** iconos emoji editables, agregar/eliminar
- **Restaurante:** habilitar/deshabilitar, descripción, menú, fotos
- **Contacto:** dirección, teléfono, email, horarios

## 📌 Pendientes / Ideas
- [ ] Botón WhatsApp flotante
- [ ] Galería Lightbox (click → pantalla completa)
- [ ] Sección de Reseñas con estrellas
- [ ] Contador animado (años, habitaciones, huéspedes)
- [ ] Botón "Volver arriba"
- [ ] Pantalla de carga elegante
- [ ] Modo oscuro
- [ ] SEO completo (meta tags, Open Graph)
- [ ] Idioma EN/ES
- [ ] Sección Promociones con cuenta regresiva

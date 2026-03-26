# 👟 On Running Lima — Landing de Venta

Landing page para venta de zapatillas On Running originales en Lima.
WhatsApp como canal principal de contacto.

## 🚀 Deploy en Vercel

### Opción 1: GitHub + Vercel (recomendado)
1. Crea un repo en GitHub y sube esta carpeta
2. Ve a [vercel.com/new](https://vercel.com/new)
3. Importa el repositorio
4. Click en **Deploy** — listo

### Opción 2: Vercel CLI
```bash
npm i -g vercel
cd on-cloud-store
vercel
```

## ✏️ IMPORTANTE: Personalizar antes de publicar

### 1. Número de WhatsApp
Busca y reemplaza `51XXXXXXXXX` por tu número real (sin el +):
```
Ejemplo: 51987654321
```
Hay ~12 ocurrencias en index.html.

### 2. Fotos reales de las zapatillas
Sube fotos de tus zapatillas reales a `public/img/` y reemplaza los emojis.
Fotos reales = más confianza = más ventas.

### 3. Instagram
Si tienes cuenta de Instagram para la venta, actualiza el link en el footer.

### 4. Actualizar stock
Cuando vendas pares, actualiza las cantidades y tallas en el HTML.

## 📋 Estructura
```
on-cloud-store/
├── public/
│   └── index.html    ← Landing page completa
├── vercel.json       ← Config de deploy
└── README.md
```

## 📱 Features
- ✅ Mobile-first responsive
- ✅ Header sticky
- ✅ Botón flotante de WhatsApp
- ✅ Catálogo con precios y comparativa vs retail
- ✅ FAQ con acordeón
- ✅ Scroll reveal animations
- ✅ SEO + Open Graph
- ✅ Redirect /wa → WhatsApp directo

## 💡 Tip
Comparte el link tudominio.vercel.app/wa para mandar gente directo a tu WhatsApp.

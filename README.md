# 3 Nuevas Micro Apps para Monetizar (2026)

Tres micro apps simples, listas para desplegar en Vercel y monetizar con freemium + Stripe.

| App | Carpeta | Descripción | Monetización |
|-----|---------|-------------|-------------|
| **QRMaker** | `qrmaker/` | Generador de códigos QR avanzado (colores, logo, alta resolución) | 5 gratis/día → Premium 4,99 €/mes ilimitado |
| **SignatureGen** | `signaturegen/` | Creador de firmas de email profesionales | Gratis básica → Premium 3,99 € (sin marca de agua + más plantillas) |
| **CountdownPro** | `countdownpro/` | Páginas de cuenta atrás personalizables para lanzamientos | Gratis con marca → Premium 6,99 € (dominio propio + sin marca) |

## Cómo publicar en Vercel

1. Ve a vercel.com → Add New Project
2. Importa este repositorio
3. Para cada app, crea un proyecto y pon el **Root Directory** en la carpeta correspondiente (`qrmaker`, `signaturegen` o `countdownpro`)
4. Deploy

Cada carpeta contiene su propio `index.html` listo para usar.

## Próximos pasos de monetización

- Añade Stripe Checkout (ver comentarios en el código)
- Usa localStorage para desbloquear premium mientras pruebas
- Añade analytics (Vercel Analytics es gratis)

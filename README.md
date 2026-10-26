# Sitio de distribución de yerba mate (La Pampa)

Sitio estático listo para Vercel. No necesita build ni dependencias.

## Estructura
```
yerba-pampa/
├── index.html   ← toda la página (HTML + CSS + JS)
├── vercel.json  ← configuración de Vercel (URLs limpias y headers)
└── README.md
```

## Qué editar antes de publicar (buscá "EDITAR" en index.html)
- Nombre de la empresa, localidad de la sede y zonas de cobertura
- Número de WhatsApp (formato internacional sin +, ej. 5492954123456)
- Marcas / variedades y formatos reales
- Email y dirección del depósito

## Publicar en Vercel
**Opción A – Panel web:** subí la carpeta a un repo de GitHub → vercel.com/new → importá el repo → Framework Preset: "Other" → Deploy.

**Opción B – CLI:**
```
npm i -g vercel
cd yerba-pampa
vercel --prod
```

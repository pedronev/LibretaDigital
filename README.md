# Libreta Digital · prototipo demostrativo

Prototipo web navegable, mobile-first, creado a partir de la identidad visual de la exportación UXPilot: fondo crema, verde profundo, verde agrícola, acento tierra y tipografía Work Sans.

## Ejecutar el proyecto

Requiere Node.js 18 o superior.

```bash
npm install
npm run dev
```

Para generar una versión de producción:

```bash
npm run build
npm run preview
```

## Desplegar en Vercel

1. Sube esta carpeta a un repositorio Git.
2. Importa el repositorio en Vercel.
3. Vercel detectará Vite automáticamente. Usa `npm run build` como comando de build y `dist` como directorio de salida.

La navegación utiliza rutas hash (`#/inicio`, `#/parcelas`, etc.), por lo que no requiere reglas especiales de redirección.

## Acceso de demostración

- Desde la primera pantalla se puede elegir **Explorar demo**.
- En el flujo de teléfono, el código de acceso simulado es `123456`.

El modo demo carga a Juan López, Rancho El Roble, Lote Norte, 24 ha de maíz en el ciclo Primavera-Verano 2026, con actividades y recordatorios de ejemplo.

## Qué es demostrativo

El prototipo no usa autenticación, SMS, servicios externos, mapas, geolocalización ni sincronización real. Toda la información se guarda solo en `localStorage` del navegador. Los indicadores de conexión, sincronización, foto, ayuda, ofertas y privacidad son interfaces demostrativas. Las exportaciones CSV/JSON y la impresión sí funcionan con los datos locales.

## Flujos incluidos

- Acceso simulado y configuración inicial de tres pasos.
- Inicio, predios, parcelas y detalle de parcela.
- Registro de actividades, con formulario completo para Aplicación de insumo.
- Historial, detalle, duplicado y eliminación de actividades.
- Agenda con creación, completado y eliminación de recordatorios.
- Registro de cosecha, cálculos y cierre de ciclo.
- Reportes locales, exportación CSV/JSON e impresión.
- Perfil, preferencias y restablecimiento de datos de demostración.
# LibretaDigital

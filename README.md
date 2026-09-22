# Inventario | TRUST

Panel interno de control e inventario de proyectos (In House / Off House).

## Puesta en marcha
1. Supabase → proyecto **Paneles** → SQL Editor → pegar y ejecutar `supabase.sql` (crea `proyectos` y `unidades`, políticas y carga inicial: 5 proyectos + 64 unidades de Balcana).
2. Subir este folder a un repo `TRUSTREAL/trust-inventario` y conectarlo a Vercel (sin build, sitio estático).
3. Abrir la URL de Vercel. El pie de página debe decir `Supabase · hh:mm`. Si dice "Modo local", revisar `SUPABASE_URL` / `SUPABASE_KEY` en `index.html`.

Misma conexión que trust-leads (publishable key, RLS abierto). Actualización automática cada 60 s y al volver a la pestaña.

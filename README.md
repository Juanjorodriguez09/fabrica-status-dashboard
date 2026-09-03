# fabrica-status-dashboard

Dashboard visual, público, de solo lectura, del estado de la fábrica de
software. Repo separado a propósito de `fabrica-status` (privado) — acá
vive únicamente el snapshot curado (`data/estado.json`, número/título/
motivo corto de cada Issue y PR), no el historial de comentarios ni
ninguna operación de la fábrica.

- **Generado por:** la Routine `reporte-diario-fabrica`, todos los días.
- **Repo operativo (privado):** `Juanjorodriguez09/fabrica-status` — ahí
  vive el subagente `pm-diario.md` y el historial completo en el Issue
  fijo `#1`.
- **Publicado en:** GitHub Pages, público porque este repo lo es — sin
  eso, Pages requiere plan pago para repos privados.

No editar `data/estado.json` a mano — se sobrescribe en cada corrida.

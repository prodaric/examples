# @prodaric/examples

**Paquete único de ejemplos** del framework Prodaric. Incluye:

- **Framework:** Dashboard, Todo list, Reportes (BIRT), Formularios (JSON Schema), CRUD, Gráficos (ECharts), Docking, Rete.js Modelo, JSON Schema (ajv), Acerca.
- **Web Components:** Shoelace (sl-*), FAST (fast-*), Vaadin (vaadin-*).

## Cómo ver los ejemplos

1. Arranca el IDE: desde la raíz del monorepo, `npm run ide` (o `npm run start` para solo navegador).
2. En la barra de menú, abre **Prodaric**.
3. Elige cualquier ítem: cada uno abre un panel en el área principal.

## Dependencias

- `@prodaric/layout`, `@prodaric/node-canvas`, `@prodaric/shell`, `@prodaric/ui-engine` — framework.
- `ajv`, `echarts` — formularios/validación y gráficos.
- `@shoelace-style/shoelace`, `@microsoft/fast-components`, `@vaadin/*` — Web Components.

Los WC se registran al cargar el frontend en `register-wc-libs.ts`.

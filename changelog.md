# Changelog

## 2026-10-15 — 5 páginas más + Santiago = mentor
### Qué cambió
- Nuevas páginas: [[creacion-de-productos-digitales]], [[diagnostico-de-checkout]], [[disputas-y-reembolsos]], [[email-y-automatizaciones]], [[embudo-vsl-post-pago]] (originales en `RAW/wiki-externo/`).
- **Santiago es el mentor** (confirmado por el usuario): actualizado en perfil, vacíos y `CLAUDE.md` (nueva sección "Contexto personal").
- Nota del bibliotecario en el embudo VSL: la ruleta "arreglada" y la barra de progreso ficticia son técnicas engañosas.
- Lista de páginas pendientes regenerada.

### Conexiones inesperadas
1. **El ejemplo de OTO de Santiago es tu propio catálogo.** "Vendiste un recetario → el OTO 1 es un curso de cómo cocinar esas recetas". Sirve directamente para Salad Dressing Bible, Baby's First Bites, panes turcos y Come y Baja: cuatro de tus once proyectos son recetarios sin upsell definido.
2. **Aroma Stones está en el nicho más fácil de upsellear.** Según el embudo VSL, "ingreso extra" siempre tiene un problema siguiente (vender, marketing). Esto refuerza la conexión con el proyecto K (finanzas del pequeño negocio) como OTO.
3. **Tus precios coinciden con los del mentor:** 27 USD en inglés es exactamente el front de su embudo en inglés. En cambio, los 19.999 ARS de Come y Baja necesitan otra vía, porque el post-pago no funciona en pesos (Impultienda).
4. **La regla "WhatsApp en LatAm, email en inglés"** encaja con tu cartera dividida: Come y Baja → WhatsApp; Salad, Baby, Macramé y Yesero → email/SMS.
5. **Lo engañoso termina en contracargos.** Las técnicas marcadas con ⚠️ (testimonios falsos, ruleta arreglada, escasez inventada) son las que más disputas generan, y el límite de contracargos es ~1%. Tus notas ya contienen el argumento en contra.

---

## 2026-10-15 — Prompts y páginas importadas
**Procesado:** `RAW/prompts/` (23 prompts + índice) y `RAW/wiki-externo/` (5 páginas de un wiki anterior).

### Qué cambió
- Nuevas páginas: [[angulos-publicitarios]], [[aumento-de-aov]], [[biblioteca-de-prompts]], [[claude-con-meta-ads]], [[contingencia-de-cuentas]]. Se respetó el texto original; los enlaces se adaptaron a las páginas existentes (ej. `modelo-low-ticket` → `modelo-de-negocio`).
- Notas del bibliotecario en la biblioteca: prompts de riesgo y la contradicción de precio 14,99 vs. 27 USD.
- Enlaces nuevos desde Meta Ads, modelo de negocio, copy y materiales de trabajo.
- [[vacios-de-informacion]]: lista de 20 páginas referenciadas que todavía faltan + duda sobre quién es "Santiago".

### Conexiones inesperadas
1. **El backend resuelve el upsell sin definir de Salad Dressing Bible.** El modelo de [[aumento-de-aov]] (5 bumps + OTO + downsell) es justo lo que les falta a los proyectos A y C, y el KPI de AOV ≥1,5× el front da un objetivo medible para el gap de "Resultados".
2. **El 90/10 de ángulos explica por qué tu feedback es "la promesa es floja".** Tu forma de trabajar (iterar sobre referencias) es el 90%. Lo que falta sistematizar es el 10% de ángulos nuevos: por ejemplo, el caso "un producto, dos mercados" aplicado a Macramé o Yesero (hobby vs. ganar dinero con el oficio).
3. **Hay un bloqueo técnico para tu modelo multi-país:** el upsell post-pago de Shopify exige el checkout en USD y desactivar Markets. Choca con Come y Baja (ARS, 6 países); la vía es Impultienda o Hotmart.
4. **El conector de Meta en Claude y el bug de Lovable son el mismo tipo de riesgo:** la herramienta dice que hizo algo (PAUSED, imágenes por país) y no lo hizo. Regla común: **verificar siempre el estado real**.

---

## 2026-10-15 — Construcción inicial del wiki
**Último procesado de RAW:** 2026-10-15 · `RAW/2026-10-15-negocio.md`

### Qué cambió
- Creado `WIKI/index.md` con 11 temas y 11 proyectos.
- 11 páginas temáticas: perfil, modelo de negocio, Meta Ads, copy, landings, localización, diseño, vídeos y voces, equipo, materiales, vacíos.
- 11 páginas de proyecto (A–K), enlazadas con `[[...]]`.

### Conexiones inesperadas
1. **El proyecto K es el upsell natural de E, F y G.** Aroma Stones, Macramé y el Manual del Yesero venden "emprender desde casa", y sus bonos ya tocan el problema de K (guía de precios, plantilla de precios, app de gestión, sistema de ventas). El cliente que compra para emprender es el mismo micro-negocio con desorden financiero que estudia K.
2. **La landing de referencia estética es la que peor retiene.** ekmek-sepeti es el modelo visual de todas las landings, pero es justo la de panes turcos, con ~9 s de permanencia. Conclusión: lo estético no alcanza; el hero manda. Además, es la única métrica real de todo el cerebro.
3. **Hay una "fábrica de ofertas" no escrita:** 27 USD + 1 producto + 3 bonos (A, C, F) y bonos en marrón / upsells en verde oscuro (E, G). Se repite tanto que podría convertirse en una plantilla estándar.
4. **Donde más se piden números es donde menos respaldo hay:** ingresos (E), peso (B), recuperación (J) y ahorro (D) son los proyectos con promesas numéricas y también los de mayor riesgo con las políticas de Meta.
5. **Hay un cluster de "familias que enseñan en casa":** C (bebés), H (alfabeto) e I (historias sociales) apuntan al mismo público angloparlante, y H e I comparten referencia (mynerdyteacher). Es una oportunidad de bundle o venta cruzada.
6. **La localización falla en la herramienta, no en el copy:** el bug de imágenes por país en Lovable (B) afectará a cualquier oferta multi-país; conviene resolverlo una vez y reutilizarlo.

## 2026-10-15
- Estructura inicial creada: `RAW/`, `WIKI/`, `OUTPUTS/`, `CLAUDE.md`.
- Añadida nota `RAW/2026-10-15-negocio.md`.

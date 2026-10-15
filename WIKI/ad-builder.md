---
tema: Ad Builder (skill de producción de creativos)
actualizado: 2026-10-15
fuentes: [RAW/skills/ad-builder/SKILL.md, RAW/skills/ad-builder/references/]
---

# Ad Builder — producción y trazabilidad de creativos

Skill instalada en `.claude/skills/ad-builder/`. **No reemplaza la metodología de [[testeo-de-creativos]]: la ejecuta.** Lo que agrega es memoria: saber **qué ángulo ganó**, no solo qué anuncio ganó.

## Las tres piezas
| Pieza | Archivo | Para qué |
|---|---|---|
| **Historial de resultados** (el corazón) | `references/historial-resultados.md` | Un bloque por producto, una fila por creativo con números reales de UTMify y veredicto. Se lee **antes** de producir y se escribe **apenas hay números** |
| **Nomenclatura** | `references/nomenclatura.md` | El ID `<ANG>-N<n>_<FMT>_H<nn>_v<N>` (ej. `ECO-N2_UGC_H03_v1`), que va en el archivo, en el nombre del anuncio en Meta (`1108 ECO-N2_UGC_H03_v1`) y en el historial |
| **Motor de producción** | `references/motor-higgsfield.md` | Estáticos (`nano_banana_pro`, 2 créditos) y UGC con workflows de Higgsfield |

Lectura de números y veredictos: `references/utmify-mapa.md`. Complementa a [[nomenclatura-del-metodo]] (que ya preveía este ID después de la fecha) y a [[tracking-y-atribucion]].

## Veredictos
✅ Validado (≥5 ventas, CPA < break-even) · 🟢 Vende · ⏳ En testeo · ❌ Descartar · 🔁 Fatigado (renovar el hook) · ⚠️ Inconcluso.

> **❌ mata el anuncio, nunca el ángulo.** Un ángulo solo es perdedor con ≥3 creativos distintos y gasto acumulado ≥ CPA break-even sin ventas. Una muestra de pre-testeo de 2 USD no alcanza para concluir nada.

## Reglas clave
- **Antes de producir:** leer el historial y la WIKI, **abrir el producto real** y chequear la economía (CPA medio = ticket ÷ 2; AOV real desde UTMify, no del precio de lista).
- **Una variable por comparación:** look nuevo → sobre un ángulo validado; ángulo nuevo → con un look validado.
- **Muestra antes del lote:** 1 pieza → OK → lote.
- **Abrir y mirar cada imagen.** Que el job diga `completed` no significa que sirva.
- **Entregar la lista de nombres de anuncio** para pegar en Meta. Sin eso, la tanda queda fuera del historial.
- **Hook = la promesa en los 3 primeros segundos**, no un buildup de dolor.
- **Zonas seguras de Meta:** arriba ~12%, abajo ~22%, derecha ~12%.

## Compliance (coincide con las notas del bibliotecario)
- **Prueba social: solo citas reales.** Nunca redactar un testimonio como si fuera de un cliente. Es la regla que faltaba en varios prompts de [[biblioteca-de-prompts]].
- Nadie de la audiencia puede ser el villano del ad.
- **Nichos de riesgo de cuenta:** salud y cuerpo (sin promesa médica, sin cifras de peso), dinero (sin "ganá X al mes"), religión (riesgo de recategorización del pixel). Se corren aislados, nunca en la cuenta que sostiene la facturación.
- Que un competidor lo corra prueba **tolerancia, no que esté permitido**.

## Estado en este cerebro
- **Instalada**, con las carpetas `CREATIVOS/entregas/` y `CREATIVOS/swipe/`.
- **El historial está vacío** y el mapa de dashboards de UTMify, sin completar.
- **Los MCP de Higgsfield y UTMify no están conectados en esta sesión en la nube.** La skill está pensada para usarse con ellos conectados (por ejemplo, desde Claude Code en tu computadora).

Relacionado: [[testeo-de-creativos]] · [[angulos-publicitarios]] · [[renovacion-de-creativos]] · [[nomenclatura-del-metodo]] · [[tracking-y-atribucion]] · [[ugc-y-video-generativo]]

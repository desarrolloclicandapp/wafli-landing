# Landing · WaFli (wafli.ai)

> Contenido textual de la landing pública. Sirve a dos momentos: **landing waitlist** (pre-lanzamiento, 5 jun - 17 jun) y **landing post-lanzamiento** (desde 17 jun, captación a creadores Fase 0 y waitlist abierta).
>
> Toda redacción tira de [`mensajes-clave.md`](./mensajes-clave.md). No reinventar copy aquí — solo aplicar.
>
> Estado: **stub con hero cerrado**. Resto de secciones a redactar por Elisa en tarea Odoo 7.2 (deadline 5 jun).
>
> Última actualización: 2026-05-05.

---

## Modos de la landing

| Modo | Activo | Diferencia clave |
|---|---|---|
| **Waitlist** | 5 jun - 17 jun | CTA principal: capturar email para early access. Sin onboarding ni signup público. |
| **Post-lanzamiento** | desde 17 jun | CTA principal: "Pruébalo 7 días gratis. Sin tarjeta." Acceso directo al onboarding. |

---

## Hero · CERRADO

### Modo waitlist

```
H1: WaFli sabe qué decir cuando tú no.

Sub: WaFli lee tu conversación de WhatsApp y te sugiere la respuesta.
     En tu español. Tú decides si la mandas.

CTA primario: Únete a la waitlist
CTA secundario: Cómo funciona (ancla a sección "Cómo funciona")

Microcopy bajo CTA: "Acceso anticipado a partir del 17 de junio."
```

### Modo post-lanzamiento

```
H1: WaFli sabe qué decir cuando tú no.

Sub: WaFli lee tu conversación de WhatsApp y te sugiere la respuesta.
     En tu español. Tú decides si la mandas.

CTA primario: Pruébalo 7 días gratis
CTA secundario: Sin tarjeta · Sin instalar nada · Funciona en tu WhatsApp

Microcopy bajo CTA: "Cancela cuando quieras desde la app."
```

---

## Sección · Pain reconocible *(stub · redactar)*

Objetivo: que el visitante se reconozca en una situación específica del ICP V1.

Material a usar:
- Casos de uso priorizados (decisiones-producto.md §2).
- Claim secundario F: *"Ese match que se enfrió porque no supiste qué decir."*
- Tres viñetas con escenarios concretos (apertura, reactivación, interpretación).

---

## Sección · Cómo funciona · 3 pasos *(stub · redactar)*

Objetivo: dejar claro que es un copiloto controlado, no un bot.

Estructura:
1. **Conectas tu WhatsApp** (código de 8 caracteres, sin instalar nada).
2. **WaFli lee la conversación** y te propone qué decir.
3. **Tú envías o editas.** WaFli nunca manda nada por ti.

Material a usar:
- Flow 3 de decisiones-producto.md §8.
- Promesa "cero configuración técnica".
- Sub-claim explicativo de mensajes-clave.md §1.

---

## Sección · Casos de uso *(stub · redactar)*

Cinco escenarios alineados con `mensajes-clave.md §3` (Propuestas de valor por caso de uso).

| Caso | Headline | Promesa |
|---|---|---|
| Match nuevo | "No sabes cómo abrir" | (de mensajes-clave.md) |
| Conversación enfriada | "Lleva 3 días sin responder" | (de mensajes-clave.md) |
| Mensaje raro | "Te ha dicho algo y no sabes qué quiere decir" | (de mensajes-clave.md) |
| Pedir cita | "Quieres proponer un plan y no sabes cómo" | (de mensajes-clave.md) |
| Lo que ya escribiste | "Suena raro, lo reescribimos" | (de mensajes-clave.md) |

---

## Sección · Por qué WaFli · diferenciadores *(stub · redactar)*

Objetivo: posicionar contra Rizz/YourMove/Plug AI sin nombrarlos. Diferenciadores defendibles de decisiones-producto.md §9.

Estructura tentativa (4 bloques):
1. **En tu WhatsApp, sin copiar y pegar.** (vs screenshot+OCR de la competencia)
2. **Lee la conversación entera, no solo el último mensaje.** (contexto completo Baileys)
3. **Habla en tu español.** (España, México, Argentina, Chile, neutro)
4. **Nunca escribe por ti.** (línea ética, decisión 1)

---

## Sección · Pricing *(stub · redactar)*

Material en decisiones-producto.md §3 (decisiones 17-24). En V0 lanzamos solo Free + Plus.

```
Free
- 5 generaciones al día
- En tu español
- Conexión con tu WhatsApp
CTA: Empezar gratis

Plus · €4.99/mes
- 150 generaciones al mes
- 7 días gratis sin tarjeta
- Top-ups de 50 generaciones por €2.99 (no caducan)
CTA: Empezar trial 7 días

Microcopy: "Cancela cuando quieras. Sin permanencia."
```

---

## Sección · FAQ *(stub · redactar)*

Las primeras 3 preguntas vienen ya desactivadas en `mensajes-clave.md §6` (las 3 objeciones EDV).

Estructura tentativa de 6-8 preguntas:
1. ¿Es seguro para mi cuenta de WhatsApp? (mensajes-clave.md §6 obj 1)
2. ¿La IA contesta por mí? (obj 2)
3. ¿Mis chats van a OpenAI? (obj 3)
4. ¿En qué países funciona? (todos los hispanohablantes)
5. ¿Qué pasa si me quedo sin generaciones? (referencia §3 decisión 21)
6. ¿Funciona en iPhone y Android? (PWA, ambos)
7. ¿Cómo cancelo? (cancelas desde la app, sin permanencia)
8. ¿Quién está detrás? (Synex Innovations LLC, USA)

---

## Footer *(stub · redactar)*

- Manifesto: *"Para los que saben que una palabra cambia la historia."* (claim C de mensajes-clave.md)
- Links: Términos · Privacidad · Soporte
- Operado por: Synex Innovations LLC.
- **No mencionar Viraltia** (decisión 25: marca propia sin paraguas Viraltia visible).

---

## SEO · meta tags *(stub · redactar)*

- Title (60 caracteres máx): "WaFli · Sabe qué decir cuando tú no"
- Meta description (155 caracteres): "Copiloto IA para tu WhatsApp. Lee la conversación, te sugiere qué decir, tú envías. En tu español, en España y LATAM. Pruébalo gratis 7 días."
- Open Graph image: pendiente identidad visual final (tarea 7.1).

---

## Notas para Elisa

- Cargar `mensajes-clave.md` antes de redactar cualquier sección.
- No introducir copy nuevo: o está aprobado en `mensajes-clave.md` o se añade ahí primero.
- Tono: tutear siempre. Cercano sin pasarse de informal.
- Validar contra frases prohibidas (`mensajes-clave.md §5`).
- Antes de publicar, pasar la lista FAQ por las 3 objeciones desactivadas (`mensajes-clave.md §6`).

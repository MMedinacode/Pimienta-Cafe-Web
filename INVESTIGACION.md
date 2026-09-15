# Cafetería Pimienta y Café — Conchalí · dossier verificado

> Verificado **en vivo en Google Maps e Instagram el 15-09-2026**.
> **Nada acá está inventado.**

## Ficha Google Maps

| Dato | Valor |
|---|---|
| Nombre | Cafeteria Pimienta y Café |
| Categoría | Cafetería |
| Dirección | Apolo 5804, 8550237 Conchalí, Región Metropolitana |
| Plus Code | J8G4+7H Conchalí |
| Teléfono | ✅ **9 5849 4408** |
| Rating | **5,0 ★** |
| Nº reseñas | 12 |
| Rango de precio | $5.000–10.000 por persona (notificado por 4 personas) |
| Servicios | Consumo en el lugar · **Retiros en la puerta** · **Entrega a domicilio** |
| Sitio web | NO tiene |

```
Place ID  : ChIJb1r5TmXHYpYRcqo9d6YNjfA
CID hex   : 0x9662c7654ef95a6f:0xf08d0da6773daa72
Coordenadas: -33.374337, -70.6935963
```

---

## 🎯 GANCHO 1: el horario partido

| Día | Horario |
|---|---|
| Lunes a viernes | **07:30 – 15:30** y **18:00 – 21:00** |
| Sábado | Cerrado |
| Domingo | Cerrado |

```js
window.HORARIO = {
  dias: ["07:30 - 15:30 y 18:00 - 21:00","07:30 - 15:30 y 18:00 - 21:00",
         "07:30 - 15:30 y 18:00 - 21:00","07:30 - 15:30 y 18:00 - 21:00",
         "07:30 - 15:30 y 18:00 - 21:00","Cerrado","Cerrado"],
  fuente: "Ficha de Google Maps, 15-09-2026"
};
```

> ✅ `horario.js` **ya soporta rangos partidos**: parte el texto por `" y "`
> (`txt.split(/\s+y\s+/i)`), así que el "abierto ahora" calcula bien las dos
> ventanas. No hubo que tocar el módulo.

**Cierran entre las 15:30 y las 18:00.** Ese hueco de dos horas y media es
exactamente el tipo de dato que se pierde en una ficha de Google y que en
una página se ve de un vistazo. Alguien que llegue a las cuatro de la tarde
se encuentra la puerta cerrada.

⚠️ La semana consultada cae en Fiestas Patrias y Google anota "El horario
podría cambiar" en viernes y sábado. El viernes igual aparece con su
horario normal. **El sábado conviene confirmarlo.**

## 🎯 GANCHO 2: el dueño responde todas las reseñas

Y responde bien. A geraldine, textual:

> "¡Muchas gracias! 😊 Qué bueno saber que disfrutaste la comida, el café y
> la atención. ¡Te esperamos pronto nuevamente!"

A C M: *"Muchas gracias 😁. Los esperamos nuevamente."*

**Es un local que ya se preocupa de su presencia online** — contesta, cuida
la ficha, tiene 5,0 limpio. Le falta el sitio, no las ganas. Para outreach
eso es lo mejor que se puede encontrar.

## Identidad: negro, amarillo limón y gatos

Entre sus fotos está **su propio banner de marca**:

> **CAFETERIA ✳ PIMIENTA Y CAFÉ ✳** — letras blancas dibujadas a mano sobre
> negro, y debajo una franja de **gatos ilustrados** en blanco, negro y
> **amarillo limón**.

Y el resto de sus fotos confirma la paleta: **mesas negras**, tablas de
madera con **base amarilla**, botellas de salsa amarilla y verde,
posavasos negros que dicen *"GOOD DAY for a…"*.

→ **Paleta muestreada con Pillow del banner:** negro `#141414` + **amarillo
limón `#FFE93D`** (el suyo mide `#FFFF5E`, se bajó un punto para que el
texto encima se lea) sobre blanco hueso.

> ⚠️ **Diferenciación vs. Churrasquería Pilón** (`#121212` + mostaza
> `#FFC21A` + ketchup): el riesgo era real, los dos son negro + amarillo.
> Se resolvió **invirtiendo la relación**: Pilón es **oscuro dominante**
> con ámbar; éste es **claro dominante** — blanco hueso de fondo, el negro
> como tinta y el amarillo limón como marcador. Y el amarillo es limón, no
> mostaza.

**Tipografía: Titan One + Inter Tight + Rock Salt.** Las tres verificadas
como no usadas (grep sobre todos los `index.html`).

**Motivo gráfico:** el trazo de marcador amarillo detrás de las palabras
clave, que es lo que hacen las manchas amarillas de su banner.

## Carta — productos reales, sin precios

⚠️ **No hay ningún precio publicado.** Ni carta fotografiada, ni menú
digital, ni redes.

Todos estos salen **nombrados textualmente en sus reseñas**:

- **Sándwich de ave palta con pollo crispy en ciabatta** — *"Prueben el
  sándwich de Ave Palta con pollo crispy en ciabatta, no se arrepentirán"*
  (geraldine). Se ve en una de sus fotos.
- **Completos con pancito casero** — *"muy buenos completos con pancito
  casero"* (C M). Se ven en tres fotos, en tabla de madera.
- **Chocolate caliente** — *"un chocolate caliente exquisito espesito"*
- **Mocachino de Nutella** — *"lo mejor"*
- **Café** y **café helado** — el helado se ve en una foto
- **Batidos** — *"tanto el café como los batidos están bien preparados"*
- **Jugos naturales** — *"sus jugos naturales un 20/10"*
- **Opciones vegetarianas** — *"cuentan con opciones vegetarianas, lo que
  se agradece siempre"*

## Reseñas reales — 3 de 3, todas 5★

1. **geraldine alexandra caamaño gonzalez** — Local Guide · 7 reseñas · 19
   fotos · hace 4 meses
   > Todo muy rico, un chocolate caliente exquisito espesito y el mocachino
   > de Nutella lo mejor! Prueben el sándwich de Ave Palta con pollo crispy
   > en ciabatta, no se arrepentirán

2. **C M** — 3 reseñas · hace 7 meses
   > muy buenos completos con pancito casero 🙏🏼 el ambiente es piola,
   > buena música y además cuentan con opciones vegetarianas, lo que se
   > agradece siempre. Tanto el café como los batidos están bien preparados.

3. **MARIA CAMILA SANCHEZ LARRAHONDO** — 2 reseñas · **hace 6 días**
   > 10/10 la verdad muy amables, el espacio es cómodo y tranquilo para
   > comerse cualquier cosa ya que todo es bueno, sus jugos naturales un
   > 20/10 ⭐️⭐️⭐️⭐️⭐️

**La tercera es de hace seis días.** El local está activo y sumando
reseñas. **Sin una sola reseña bajo 5 estrellas** y sin red flags.

## ⚠️ OJO CON EL INSTAGRAM — no es el suyo

**`@pimientaycafe` EXISTE pero es de otro negocio.** Verificado el
15-09-2026: es un **restaurante de comida típica colombiana en Bogotá**
(*"Carrera 3 Num: 9-27 Bogotá Centro"*, 78 seguidores).

**No se usó en el sitio, y Matías no debe escribirle.** No se encontró
ninguna red social verificable de la cafetería de Conchalí.

→ **Aprendizaje:** que el handle coincida con el nombre no basta. **Hay que
abrir el perfil y leer la dirección de la bio** antes de publicarlo.

## Fotos reales → `fotos/` (5 usables)

| Archivo | Qué es |
|---|---|
| `hero-pollo-crispy.jpg` | **El sándwich de pollo crispy con palta en ciabatta**, en tabla — es el que recomienda la reseña, y es el hero |
| `banner-marca.jpg` | **Su banner de marca**: "Cafetería Pimienta y Café" en negro, con la franja de gatos amarillos |
| `completos-mesa.jpg` | Dos completos en tabla con base amarilla, sobre mesa negra |
| `mesa-compartida.jpg` | Cuatro completos servidos, con las botellas de salsa |
| `cafe-helado.jpg` | Café helado en vaso alto |

⚠️ En `completos-mesa.jpg` y `mesa-compartida.jpg` **se ven manos, brazos y
torsos de clientes, pero ninguna cara** — el encuadre corta antes. Pasan la
regla, aunque conviene pedirles fotos sin gente igual.

## Lo que falta por verificar

- [ ] **Precios**: no consta ninguno. Es lo primero que falta.
- [ ] **Redes propias**: no se encontró ninguna (ver advertencia arriba).
- [ ] **El sábado**: confirmar si de verdad cierran.
- [ ] Fotos del salón sin clientes.

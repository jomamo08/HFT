# Plan de publicación y análisis

## 1. Preparación (una sola vez)

- [ ] **Mismo nombre de usuario en las 3 plataformas** (por ejemplo `@[nombre]rblx`).
- [ ] **Tipo de cuenta en TikTok.** Con cuenta *Business* tienes link en la bio desde el primer día, pero solo música comercial. Con cuenta personal tienes toda la música, pero no hay link hasta los 1.000 seguidores. Mi recomendación: empieza con la personal, porque al principio pesa más el sonido en tendencia que un link en el que casi nadie hace clic.
- [ ] **Bio en las 3:** `Dev de [NOMBRE] en Roblox 🎮 Búscalo en Roblox 👇`, con el link donde se pueda (Instagram, canal de YouTube, TikTok si se puede).
- [ ] **Share links en Roblox**, uno por sitio: `tiktok-bio`, `instagram-bio` y `youtube-canal`.
- [ ] **Códigos en el juego:** `TIKTOK`, `REELS` y `SHORTS`, que den el mismo premio, y un evento de analíticas cada vez que alguien canjea uno.
- [ ] **Prueba de búsqueda:** el juego aparece al buscar `[NOMBRE]` en Roblox desde otra cuenta.
- [ ] **Anota las cifras de partida:** visitas al día y jugadores nuevos al día de la última semana. Sin ellas no podremos saber si los vídeos han tenido efecto.

## 2. Calendario de la semana de prueba

| Día | Qué |
|---|---|
| 1 | **Vídeo 1** en TikTok, Reels y Shorts, a la **misma hora** en las 3 |
| 2 | **Vídeo 2** en las 3 |
| 3 | **Vídeo 3** en las 3 (el admin abuse grabado ese mismo día o el anterior) |
| 1-7 | Responder a **todos** los comentarios durante la primera hora después de publicar |
| 4-6 | 1 o 2 vídeos de respuesta a comentarios (rápidos de hacer y alimentan el algoritmo) |
| 7 | Recoger métricas y analizarlas juntos |

**Hora:** empieza por la tarde-noche del país de tu público (entre las 17:00 y las 21:00 entre semana, algo antes el fin de semana). El público de Roblox es joven y está en clase por la mañana. Cuando tengas datos, ajústala con la sección de "cuándo está activa tu audiencia" de cada plataforma.

## 3. Qué medir y dónde encontrarlo

Apunta los datos en [`metricas.csv`](./metricas.csv) **a las 24 h, a las 72 h y a los 7 días** de cada publicación.

| Dato | TikTok (TikTok Studio) | Instagram (Estadísticas del reel) | YouTube (YouTube Studio) |
|---|---|---|---|
| **¿Pasan del gancho?** | Gráfica de retención: cuánta gente queda en el segundo 2-3 | *Tasa de omisión* (skip rate), si te aparece | **Visto vs. deslizado** |
| **¿Lo terminan?** | % que vio el vídeo completo y tiempo medio de visualización | Tiempo medio de visualización | % medio visto |
| **¿Reaccionan?** | Compartidos, guardados y comentarios | Compartidos, guardados y comentarios | Comentarios y "me gusta" |
| **¿Te siguen?** | Visitas al perfil y seguidores nuevos | Visitas al perfil y seguidores nuevos | Suscriptores ganados |

**En Roblox** (Creator Dashboard → Analytics):
- *Acquisition → Share links*: jugadores que entraron por cada link, su tiempo de juego y la retención D7.
- Canjes de cada código (`TIKTOK`, `REELS`, `SHORTS`).
- Jugadores nuevos al día comparados con las cifras de partida.

## 4. Cómo diagnosticar qué mejorar

Revisa los pasos en orden: el primero que falle es lo que hay que arreglar en la siguiente tanda.

| # | Síntoma | Causa probable | Qué cambiamos |
|---|---|---|---|
| 1 | Mucha gente desliza en los 2-3 primeros segundos (en Shorts, menos del 60-70 % en "visto"; en TikTok, la gráfica cae en picado al principio) | **El gancho** | Otro primer plano más caótico, el texto más corto y grande, empezar todavía más metido en la acción |
| 2 | Pasan el gancho pero no lo terminan (menos del 40-50 % completo en vídeos de 15-25 s) | **La parte del medio es lenta** | Recortar, planos más cortos, quitar todo lo que no sea acción |
| 3 | Muchas vistas, pero pocos comentarios y compartidos | **No hay emoción ni pregunta** | Pregunta más directa, una decisión polémica, más reacciones reales |
| 4 | El vídeo va bien, pero no llega casi nadie al juego (pocos canjes y pocas visitas por los share links) | **La llamada a la acción o la búsqueda** | Nombre del juego más visible y más tiempo en pantalla, enseñar cómo se busca, revisar que salga al buscarlo |
| 5 | Llegan al juego pero se van enseguida (poco tiempo de juego, D1 o D7 bajas) | **El juego no cumple lo que promete el vídeo** (no es un problema de marketing) | Que lo del vídeo pase en los primeros 30 s de partida. Revisar el tutorial y la primera recompensa |
| 6 | Una plataforma va mucho mejor que las demás | Esa plataforma encaja mejor con tu público | Publicar más ahí y adaptar el formato |

> Los porcentajes son **orientativos**, sacados de guías de 2025-2026. A partir de unos 10 vídeos, la referencia buena será **tu propia media**.

## 5. Cómo iteramos

1. **Cambia una sola cosa cada vez** (el gancho, la duración, el formato o la hora). Si cambias varias, no sabremos qué ha funcionado.
2. Después de los 3 primeros vídeos:
   - Coge el **formato ganador** y haz 3 variantes con ganchos distintos.
   - Repite una vez el formato intermedio con un gancho mejor.
   - Abandona (de momento) el formato que peor haya ido.
3. Repite el ciclo cada semana.

## 6. Cómo me pasas los datos

Elige lo que te resulte más cómodo:
- Rellena `metricas.csv` y dime "ya está", o
- Mándame **capturas** de las estadísticas de cada vídeo (TikTok Studio, Instagram, YouTube Studio y el dashboard de Roblox).

Con eso hago el diagnóstico de la sección 4 y te preparo los guiones de la siguiente tanda.

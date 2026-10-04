# Estrategia de vídeo corto para el juego de Roblox (TikTok, Reels, Shorts)

Resumen de lo que ha funcionado con juegos de Roblox y cómo lo aplicamos. Las fuentes están al final.

## 1. Casos que han funcionado y qué copiamos

| Caso | Qué hicieron | Qué copiamos |
|---|---|---|
| **Grow a Garden** (Jandel, @jandelrblx) | El desarrollador se convirtió en personaje público en TikTok: publicaba "leaks" de la próxima actualización ("esto es un leak de algo que estamos pensando añadir"), avisos de "update en unas horas" y eventos de **Admin Abuse**. Llegó a 7,5 M de seguidores en semanas. | Tú das la cara (o la voz) como dev. Cuentas lo que viene y dejas que la comunidad opine. Hacemos eventos de admin para grabarlos. |
| **Steal a Brainrot** | Se hizo viral con clips de estrategia y, sobre todo, con **reacciones reales** de jugadores (niños llorando porque les robaban sus brainrots). Usaba memes que la gente ya conocía. | Enseñar emociones de jugadores reales (rabia, risa, sustos), no solo gameplay bonito. |
| **Juegos de terror multijugador** | Bucle viral: los jugadores gritan, lo graban, lo suben a TikTok y traen a sus amigos. El chat de voz por proximidad ayuda. | Diseñar momentos "clipeables" dentro del juego y grabarlos. |
| **Bomb Click, Lying Challenge, Rubber Band Watermelon** | Tendencias de TikTok convertidas en minijuegos de Roblox. Bomb Click superó los 260 M de visitas. | Si hay una tendencia que encaje con tu juego, montamos el vídeo (o una mecánica) sobre ella. |

## 2. Principios que se repiten en todas las fuentes

1. **Gancho en 1-2 segundos.** La gente desliza muy rápido. Empieza en mitad de la acción, con gameplay real desde el primer frame. Nada de logos ni intros.
2. **Sin contexto.** Cada vídeo tiene que entenderse solo, como si el espectador no te conociera de nada (y no te conoce).
3. **Ritmo rápido.** Planos de 2 a 5 s como máximo y vídeos de 15 a 30 s al principio, porque un vídeo corto se termina más veces.
4. **Final en bucle.** Que el último plano empalme con el primero. Así se vuelve a ver, y el algoritmo valora mucho que se vea más de una vez.
5. **Comentarios y compartidos pesan más que los "me gusta".** Cada vídeo termina con una pregunta o una decisión que invite a comentar.
6. **Subtítulos grabados en el vídeo.** Mucha gente lo ve sin sonido. El texto va fuera del 20 % inferior y del lateral derecho, donde están los botones.
7. **Constancia.** Lo ideal es publicar a diario. Las agencias dicen que con 3 publicaciones al día se consiguen unas 4 veces más visitas, pero ese dato viene de una agencia que vende promoción: tómalo como "publicar más ayuda", no como algo garantizado.
8. **Un vídeo, tres plataformas.** Sube el **archivo original** a cada sitio, nunca uno descargado de TikTok con marca de agua (Instagram y YouTube los muestran menos).

## 3. Diferencias entre plataformas que nos afectan

| | TikTok | Instagram Reels | YouTube Shorts |
|---|---|---|---|
| **Link clicable** | En la bio, solo con cuenta **Business** (sin mínimo de seguidores) o con **1.000+ seguidores**, y siendo mayor de 18. | En la bio, para todos. En la descripción no es clicable. | **No** es clicable en la descripción ni en los comentarios. Se usan los enlaces del canal y la opción de "vídeo relacionado". |
| **Vida del vídeo** | El pico dura entre 24 y 72 h. | Parecido a TikTok. | Sigue sumando vistas durante meses, porque se puede buscar en YouTube y Google. |
| **Ojo con** | La cuenta Business solo puede usar la *Commercial Music Library*. | Penaliza los vídeos con marca de agua de TikTok. | El título debe llevar el nombre del juego y la palabra "Roblox" para salir en las búsquedas. |

**Conclusión:** casi nadie va a hacer clic en un enlace, así que la llamada a la acción principal es hablada y escrita: **"Búscalo en Roblox: [NOMBRE]"**. Por eso el nombre del juego tiene que ser fácil de buscar (ver la sección 4).

## 4. Qué preparar en Roblox antes de publicar

1. **El juego tiene que enganchar.** La propia documentación de Roblox dice que, antes de traer jugadores, la retención y el tiempo de sesión tienen que estar bien. La sección *Home* recomienda juegos según la retención del día 1 y el tiempo de sesión. Si alguien llega desde TikTok y se va al minuto, no te sirve de nada.
2. **Los primeros 30 s de partida tienen que cumplir lo que promete el vídeo.** Si el vídeo enseña caos, el jugador debe ver caos enseguida, no un tutorial de 3 minutos.
3. **Que se pueda encontrar buscando.** Busca el nombre exacto del juego en Roblox desde una cuenta que no sea la tuya. Si no sale de los primeros, plantéate un nombre más único o añadir una palabra clave.
4. **Un share link por plataforma** (Creator Dashboard → Creations → *Share Links* → *Create link*). No hay límite de enlaces. En *Analytics → Acquisition → Share links* puedes ver, para cada enlace, los usuarios que jugaron, el tiempo de juego en 7 días, la retención a 7 días (D7) y los ingresos a 30 días por usuario.
   - Opcional: con *custom LaunchData* puedes dar un premio dentro del juego a quien entre por ese enlace (se lee con `Player:GetJoinData()`).
5. **Un código por plataforma** (por ejemplo `TIKTOK`, `REELS`, `SHORTS`) que dé una recompensa pequeña. Como la mayoría llegará buscando el juego y no por un enlace, el código es la única forma de saber de qué plataforma vienen. Contamos los canjes con `AnalyticsService:LogCustomEvent` (puedo programarlo en Luau).
6. **Social links en la página del juego.** Solo se admiten Facebook, X/Twitter, YouTube, Twitch, Discord, Guilded y comunidades de Roblox; **TikTok e Instagram no están**. Para añadirlos tienes que verificar que tienes 16 años o más, y solo los ven los usuarios verificados de 16+. Dentro del juego **no se pueden poner enlaces**. Sí se puede escribir "links en la página del juego".

## 5. Qué NO copiar

- No resubas clips de otros creadores ni de otros juegos.
- No digas cosas falsas como "solo el 1 % lo consigue" si no es verdad. Saca el porcentaje real de tus analíticas o usa "casi nadie pasa esta parte". Además, el clickbait que el juego no cumple hace que la gente se vaya enseguida, y eso hunde tu posición en Roblox.
- No compres seguidores ni vistas.
- Ten cuidado con los otros jugadores: muchos son menores. No publiques sus voces ni sus nombres de usuario sin difuminar. Usa el chat de texto con los nombres tapados.

## Fuentes

- [Steal a Brainrot (Wikipedia)](https://en.wikipedia.org/wiki/Steal_a_Brainrot)
- [Grow a Garden (Wikipedia)](https://en.wikipedia.org/wiki/Grow_a_Garden)
- [Dexerto: Who is Jandel on TikTok?](https://www.dexerto.com/tiktok/who-is-jandel-on-tiktok-grow-a-garden-roblox-game-creator-goes-viral-3227238/)
- [TikTok: Jandel reveals Grow a Garden update](https://www.tiktok.com/en/trending/detail/jandel-reveals-roblox-grow-a-garden-update)
- [Rolearn: Roblox game case studies](https://rolearn.dev/case-studies/)
- [How To Market A Game (Chris Zukowski): 7 tips for TikTok](https://howtomarketagame.com/2022/02/07/seven-great-tips-for-marketing-your-indie-game-on-tiktok/)
- [Eklipse: Roblox YouTube Shorts strategy 2026](https://blog.eklipse.gg/beginner-guide-2/roblox-youtube-shorts-strategy.html)
- [Bloxg: Roblox TikTok marketing guide](https://bloxg.com/guides/roblox-tiktok-marketing) (es una agencia: sus cifras son orientativas)
- [Roblox Creator Docs: Share links](https://create.roblox.com/docs/production/promotion/share-links)
- [Roblox Creator Docs: Social media links](https://create.roblox.com/docs/production/promotion/social-media-links)
- [Roblox Creator Docs: Acquisition](https://create.roblox.com/docs/production/analytics/acquisition)
- [Requisitos del link en la bio de TikTok (Stan, 2026)](https://stan.store/blog/tiktok-link-bio-requirements-2026-guide/)
- [Links en YouTube Shorts (TubeBuddy)](https://www.tubebuddy.com/blog/youtube-shorts-link-changes/)
- [Algoritmo de TikTok 2026 (Darkroom)](https://www.darkroomagency.com/observatory/how-tiktok%E2%80%99s-algorithm-works-in-2026-and-15-tactics-to-go-viral)

# Emerald Rogue EX — Traducción al castellano

*[English version below](#english-version)*

Traducción no oficial al **castellano de España** de **Emerald Rogue EX v2.2.1a**, el *roguelite* basado en Pokémon Esmeralda creado por **[Pokabbie](https://github.com/Pokabbie/pokeemerald-rogue)**.

> Todo el juego (diseño, programación, contenido, gráficos y equilibrio) es obra de **Pokabbie** y de quienes han colaborado en Emerald Rogue. Este parche **solo traduce los textos y los gráficos con texto** y hace los ajustes de código imprescindibles para que el castellano quepa y se vea bien. Si te gusta el juego, apoya el proyecto original.

Hilo del proyecto en Whack a Hack!: **[Emerald Rogue EX v2.2.1a — Traducción al castellano](https://whackahack.com/foro/threads/emerald-rogue-ex-v2-2-1a-traduccion-al-castellano.69359/)**. Ahí puedes comentar, dar sugerencias o avisar de errores.

---

## Qué está traducido

- **Diálogos de Rogue**: la base, los laboratorios, la tienda de ropa, la panadería, la escuela, los eventos de aventura, los tutoriales, etc.
- **Misiones** y **entrenadores**: nombres de misiones, descripciones y todas las frases de los Líderes, el Alto Mando, los Campeones, los rivales y los equipos villanos.
- **Menús e interfaz**: menú principal, opciones, ajustes de Rogue, tablero de misiones, estadísticas, recuadro del menú START, Pokédex de Rogue, avisos emergentes, personalización del personaje…
- **Combate**: todos los mensajes, los menús de combate, la eficacia de los movimientos, los tipos y los climas.
- **Nombres oficiales** de movimientos (incluidos los movimientos Z y Gigamax al usarlos en combate), habilidades, objetos, bayas, naturalezas, clases de entrenador y categorías de especie.
- **Descripciones** de movimientos, habilidades, objetos (incluidas las megapiedras nuevas de Leyendas Z-A) y bayas.
- **Decoraciones de la casa**: nombres de las decoraciones, de sus variantes y de sus grupos.
- **Créditos finales**, con su sección de la traducción, y el cartel del final: "¿FIN?" (o "FIN" con todas las misiones completas), dibujado con las mismas piezas que el "THE END?" original.
- **Nombres de personajes** con su versión oficial en España (por ejemplo, Blasco, Máximo, Treto o Aria).
- **Textos de sistema de Pokémon Esmeralda que Rogue sigue usando**: guardar partida, interacciones del mapa (rocas, árboles, cascadas, Surf, Buceo), Centro Pokémon, bayas, PC, Repelente, Buscapelea, la presentación del Prof. Abedul y los avisos de la Zona Safari.
- **Gráficos con texto**, tomados de Pokémon Edición Esmeralda en castellano para que se vean igual que en el juego original:
  - "PULSA START" de la pantalla de título.
  - Iconos de tipos y de categorías de concurso, y etiquetas TIPO / POTENC. / PRECIS. / EFECTO.
  - Iconos de estado (ENV, PAR, DOR, CON, QUE, DEB).
  - Pantalla de datos del Pokémon (PERFIL, HABILIDAD, CARACTERÍST., EXPERIENCIA, MOVIMIENTOS, DESCRIPCIÓN…).
  - Ficha de entrenador, menú de las cajas y botones del teclado de nombres.
  - Etiquetas MT, DT y MO del bolsillo de máquinas de la Mochila.
  - Pantalla de intercambio y aviso de emulador poco preciso ("¡AVISO!").
  - Propios de Rogue, redibujados con su mismo estilo de letra: "PS" de la barra de vida, iconos de teratipo (LUCHA, VOLAD, FUEGO…), estados DOR y QUE del marcador de combate y botón "NOTAS" de Giravoltorb.
  - Lo que no existe en Esmeralda se ha dibujado con las mismas letras: tipos HADA y ASTRAL, estado CGL (congelación), AMISTAD, "MISIONES" del libro de misiones y "A·ABRIR / SELECT·EDITAR" de la Pokédex de Rogue.

### Criterios de la traducción

- **Castellano de España** y terminología oficial de los juegos.
- **Nombres oficiales**:
  - Los nombres y abreviaturas cortas se han comprobado con Pokémon Edición Esmeralda en castellano.
  - Los de generaciones posteriores se han comprobado con [WikiDex](https://www.wikidex.net) y con los datos en castellano de España (idioma `es`) de [PokeAPI](https://pokeapi.co).
- **Descripciones de movimientos y habilidades**:
  - Se usa el texto oficial de los juegos recopilado en [PkParaíso](https://pkparaiso.com): el de 5ª generación y, si no cabe, el de 4ª o el de 3ª (Esmeralda), siempre que describa cómo funciona en Rogue.
  - Si ninguno cabe, se usa la descripción oficial en castellano de España de PokeAPI **resumida** para las ventanas de GBA.
- **Descripciones de objetos**: descripciones oficiales de PokeAPI, resumidas hasta el ancho real del cuadro de la Mochila (102 px, el mismo que en Esmeralda).
- **Textos propios**: donde el texto oficial describe una mecánica que Rogue cambia (congelación, turnos de las ataduras, efectos de Ácido y Triturar…) o se refiere a otro juego, se ha redactado un texto propio.
- **Límites de GBA**:
  - Los nombres largos se abrevian al estilo de los juegos de GBA ("Pantalla Humo", "Colmillo Ven.", "Torm. Arena").
  - Todo se ha medido en píxeles con las fuentes reales del juego para que nada se corte (las descripciones de movimientos, a la ventana más estrecha en que aparecen: la de aprender movimientos).
- **Mensajes de combate** con la estructura del Esmeralda en castellano: "¡Ataque de Zigzagoon bajó!", "¡Defensa de Zigzagoon bajó mucho!".
- **Abreviaturas de características**: PS, Atq, Def, At. Esp, Df. Esp, Vel.

---

## Cómo jugar

Este repositorio solo contiene el parche **`emeraldrogue_ex_es.ups`**. Descárgalo desde la sección [Releases](https://github.com/SeCaVa/EmeraldRogue-Castellano/releases/latest).

1. Consigue tu propia ROM de **Pokémon Emerald (USA, Europe)** (la versión inglesa, no la española).
   - CRC32: `1F1C08FB`
2. Aplica el parche con [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/) u otro programa compatible con parches UPS.
3. Juega la ROM resultante en un emulador preciso (por ejemplo, mGBA) o en una consola.

**Este repositorio no incluye ninguna ROM.**

---

## Qué no está traducido

- **Entradas de la Pokédex**: Emerald Rogue no las incluye en la ROM.
- **Funciones de Pokémon Esmeralda que Rogue no usa**: Sala Unión, Regalo Misterioso, PokéNav, televisión, Frente Batalla y Pase Frontera, Pokédex original, casino, concursos, caja de Pokécubos, Tritura Bayas, decoraciones de la base secreta y los mapas originales de la Zona Safari (textos y gráficos).
- **Logotipos**: el logotipo del título, el de pokeemerald-expansion y el de la Pokédex se dejan como en el original.

Si encuentras un texto sin traducir, cortado o con errores, abre una *issue* en este repositorio.

---

## Créditos

- **Emerald Rogue / Emerald Rogue EX**: [Pokabbie](https://github.com/Pokabbie/pokeemerald-rogue) y colaboradores. Todo el mérito del juego es suyo.
- **pokeemerald-expansion**: [RHH (ROM Hacking Hideout)](https://github.com/rh-hideout/pokeemerald-expansion) y su [lista de colaboradores](https://github.com/rh-hideout/pokeemerald-expansion/wiki/Credits). Emerald Rogue se basa en su proyecto.
- **pokeemerald**: el proyecto de descompilación de [pret](https://github.com/pret/pokeemerald).
- **Datos de referencia**: [PokeAPI](https://pokeapi.co), [PkParaíso](https://pkparaiso.com) y [WikiDex](https://www.wikidex.net) para los nombres y las descripciones oficiales en castellano; Pokémon Edición Esmeralda en castellano para los nombres cortos, los mensajes de sistema y los gráficos con texto.
- **Fuente del logotipo de la traducción**: [Jost](https://fonts.google.com/specimen/Jost), de Owen Earl (licencia SIL Open Font License).
- **Traducción al castellano**: SeCaVa.

☕ Si quieres apoyar mi trabajo como traductor, puedes hacerlo en [Ko-fi](https://ko-fi.com/secava) o [GitHub Sponsors](https://github.com/sponsors/SeCaVa). Es totalmente voluntario: la traducción es y seguirá siendo gratis. Y si te gusta el juego, apoya también el proyecto original de Pokabbie.

---

## Aviso legal

Proyecto hecho por fans y sin ánimo de lucro. No está afiliado ni respaldado por Nintendo, Game Freak, The Pokémon Company, Pokabbie ni RHH. Pokémon y todos los nombres relacionados son marcas registradas de sus respectivos propietarios. Este repositorio no distribuye ROMs, solo un parche.

---
---

## English version

Unofficial **Castilian Spanish** (Spain) translation of **Emerald Rogue EX v2.2.1a**, the Pokémon Emerald-based *roguelite* created by **[Pokabbie](https://github.com/Pokabbie/pokeemerald-rogue)**.

> The whole game (design, programming, content, graphics and balance) is the work of **Pokabbie** and the Emerald Rogue contributors. This patch **only translates the text and the graphics that contain text**, plus the minimum code changes needed for Spanish to fit and display correctly. If you enjoy the game, please support the original project.

Project thread on Whack a Hack! (in Spanish): **[Emerald Rogue EX v2.2.1a — Traducción al castellano](https://whackahack.com/foro/threads/emerald-rogue-ex-v2-2-1a-traduccion-al-castellano.69359/)**. Feel free to leave comments, suggestions or bug reports there.

### What is translated

- **Rogue dialogue**: the hub, the labs, the clothes shop, the bakery, the school, adventure events, tutorials, etc.
- **Quests** and **trainers**: quest names, descriptions and every line of the Gym Leaders, Elite Four, Champions, rivals and villain teams.
- **Menus and UI**: main menu, options, Rogue settings, quest board, stats, START menu info box, Rogue Pokédex, pop-ups, character customisation…
- **Battle**: all messages, battle menus, move effectiveness, types and weather.
- **Official Spanish names** of moves (including Z-Moves and G-Max moves when used in battle), abilities, items, berries, natures, trainer classes and species categories.
- **Descriptions** of moves, abilities, items (including the new Legends Z-A Mega Stones) and berries.
- **Home decorations**: decoration, variant and group names.
- **End credits**, with a translation section, and the closing card: "¿FIN?" (or "FIN" once every quest is complete), built from the same tiles as the original "THE END?".
- **Character names** using their official Spanish (Spain) versions (e.g. Blasco, Máximo, Treto, Aria).
- **Pokémon Emerald system text still used by Rogue**: saving, map interactions (rocks, trees, waterfalls, Surf, Dive), Pokémon Center, berries, PC, Repel, VS Seeker, Prof. Birch's introduction and Safari Zone prompts.
- **Graphics containing text**, taken from the Spanish release of Pokémon Emerald so they look like the original game: "PULSA START", type and contest icons, TIPO / POTENC. / PRECIS. / EFECTO labels, status icons, summary screen, trainer card, PC box menu, naming screen buttons, the MT / DT / MO labels in the Bag, the trade screen and the inaccurate-emulator warning ("¡AVISO!"). Rogue's own graphics were redrawn in their original lettering: the "PS" (HP) label on the health bar, the Tera type icons, the DOR/QUE (sleep/burn) battle status labels and Voltorb Flip's "NOTAS" button. Graphics that don't exist in Emerald (Fairy and Stellar types, frostbite status, friendship label, the quest book title and the Rogue Pokédex hints) were drawn with the same lettering.

### Translation guidelines

- **Spanish from Spain** and the games' official terminology.
- **Official names**: checked against the Spanish release of Pokémon Emerald and, for later generations, against [WikiDex](https://www.wikidex.net) and the Spanish (Spain) data from [PokeAPI](https://pokeapi.co).
- **Move and ability descriptions**: official in-game text collected by [PkParaíso](https://pkparaiso.com), using the Gen 5 text or, if it doesn't fit, the Gen 4 or Gen 3 (Emerald) one, as long as it matches how the move or ability works in Rogue. When none fits, the official PokeAPI text is **condensed** to fit the GBA windows.
- **Item descriptions**: official PokeAPI texts, condensed to the real width of the Bag window (102 px, the same as in Emerald).
- **Own wording**: where the official text describes a mechanic Rogue changes, or refers to another game, the description was written from scratch.
- **GBA limits**: long names are abbreviated GBA-style, and everything was measured in pixels with the game's actual fonts so nothing gets cut off.
- **Battle messages** follow the structure of the Spanish Emerald ("¡Ataque de Zigzagoon bajó!").

### How to play

This repository only contains the **`emeraldrogue_ex_es.ups`** patch. Download it from [Releases](https://github.com/SeCaVa/EmeraldRogue-Castellano/releases/latest).

1. Get your own **Pokémon Emerald (USA, Europe)** ROM (the English release, not the Spanish one).
   - CRC32: `1F1C08FB`
2. Apply the patch with [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/) or any other UPS patcher.
3. Play the patched ROM on an accurate emulator (e.g. mGBA) or on hardware.

**This repository contains no ROMs.**

### Not translated

- **Pokédex entries**: Emerald Rogue doesn't include them in the ROM.
- **Pokémon Emerald features Rogue doesn't use**: Union Room, Mystery Gift, PokéNav, TV, Battle Frontier and Frontier Pass, the original Pokédex, Game Corner, contests, Pokéblock case, Berry Crush, secret base decorations and the original Safari Zone maps (text and graphics).
- **Logos**: the title screen, pokeemerald-expansion and Pokédex logos are left as in the original.

If you find untranslated, cut-off or wrong text, please open an issue in this repository.

### Credits

- **Emerald Rogue / Emerald Rogue EX**: [Pokabbie](https://github.com/Pokabbie/pokeemerald-rogue) and contributors. All credit for the game goes to them.
- **pokeemerald-expansion**: [RHH (ROM Hacking Hideout)](https://github.com/rh-hideout/pokeemerald-expansion) and its [contributors](https://github.com/rh-hideout/pokeemerald-expansion/wiki/Credits). Emerald Rogue is built on their project.
- **pokeemerald**: the [pret](https://github.com/pret/pokeemerald) decompilation project.
- **Reference data**: [PokeAPI](https://pokeapi.co), [PkParaíso](https://pkparaiso.com) and [WikiDex](https://www.wikidex.net) for official Spanish names and descriptions; the Spanish release of Pokémon Emerald for short names, system messages and text graphics.
- **Translation logo font**: [Jost](https://fonts.google.com/specimen/Jost) by Owen Earl (SIL Open Font License).
- **Spanish translation**: SeCaVa.

☕ If you'd like to support my work as a translator, you can do so on [Ko-fi](https://ko-fi.com/secava) or [GitHub Sponsors](https://github.com/sponsors/SeCaVa). It's completely optional: the translation is and will always be free. And if you enjoy the game, please support Pokabbie's original project too.

### Legal notice

Non-profit fan project. Not affiliated with or endorsed by Nintendo, Game Freak, The Pokémon Company, Pokabbie or RHH. Pokémon and all related names are trademarks of their respective owners. This repository does not distribute ROMs, only a patch.

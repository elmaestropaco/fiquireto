# ⚗️ FiQuiReto · Retos Interactivos de Física y Química

**FiQuiReto** es una aplicación web interactiva y gamificada de retos de **Física y Química** para Educación Secundaria Obligatoria (ESO), basada directamente en los contenidos, talleres y ejercicios del libro de texto.

---

## 🎯 Características Principales

- **Nombre Oficial:** **FiQuiReto** (Física y Química + Reto).
- **Favicon Integrado:** Incluye favicon vectorial SVG (matraz químico con gradiente cian-violeta y burbujas reactivas) insertado tanto en formato archivo [`favicon.svg`](file:///home/usuario/Escritorio/VibeCode/F%C3%ADsica%20y%20Qu%C3%ADmica/Retos%20WebApp/favicon.svg) como embebido en base URI en el propio HTML para verse de inmediato incluso al abrir el archivo en local.
- **100% Autocontenida (Zero Dependencies):** No necesita librerías externas ni CDNs. Funciona tanto online como offline directamente en cualquier navegador moderno.
- **Iconos Vectoriales Universales (SVG):** Todos los botones y categorías usan iconos vectoriales SVG limpios. Esto asegura que se vean con total nitidez en cualquier sistema operativo (Linux, Windows, macOS, Android, iOS, Chromebooks) sin depender de si el sistema tiene o no instaladas fuentes de emojis como Noto Color Emoji.
- **108 Retos Exclusivos de Física y Química:** 12 preguntas por cada uno de los 9 apartados temáticos del Tema 1 del libro:
  1. 🔮 **Ciencia y Pseudociencia:** Conocimiento científico, leyes, taller del huevo y la sal (densidad), pseudociencias (lentejas, horóscopos, cabañuelas, homeopatía, criptozoología, agricultura biodinámica).
  2. ⚛️ **Grandes Científicos y Científicas:** Arquímedes, Ptolomeo, Hipatia de Alejandría, Copérnico, Galileo, Newton, Lavoisier y Marie-Anne Paulze, Dalton, Maxwell, Marie Curie, Einstein y Niels Bohr.
  3. 🔬 **El Método Científico:** Las 6 fases ordenadas, hipótesis contrastables, taller del vaso invertido con agua y papel (presión atmosférica), control de variables y reproducibilidad.
  4. 🧪 **El Trabajo en el Laboratorio:** Báscula/balanza, probeta, pipeta, matraz Erlenmeyer, vaso de precipitado, tubo de ensayo, mechero Bunsen, mortero, gradilla, escobilla, termómetro, cronómetro, soporte universal; volumen de sólidos irregulares por inmersión.
  5. ⚠️ **Normas de Seguridad y Pictogramas:** EPI y conducta segura en el laboratorio; pictogramas oficiales CLP/GHS (inflamable, comburente, explosivo, corrosivo, tóxico agudo con calavera, irritante/nocivo con exclamación, peligro grave a largo plazo, medio ambiente acuático).
  6. 📏 **El Sistema Internacional (SI):** Concepto de medir, origen histórico del metro y kilogramo, las 7 magnitudes fundamentales ($m, kg, s, A, K, mol, cd$), magnitudes derivadas y volumen ($m^3$, $L$, $dm^3$, $mL$).
  7. 🔢 **Múltiplos y Submúltiplos:** Escala decimal ($k, h, da, d, c, m$), concurso de tartas de queso de Cuenca ($dag, hg, dg$), factores de conversión de longitud, masa, volumen y tiempo.
  8. 🎯 **Medidas Directas, Estimación y Error:** Medida directa vs indirecta (fórmulas, huella ecológica, temperatura del Sol), aproximaciones por exceso y por defecto, cálculo de errores (distancia Gijón-Jaén, la hucha de 78 € y raciones de arroz).
  9. 📊 **Tablas, Gráficas y Comunicación:** Tablas de datos, gráficas cartesianas, leyes y fórmulas ($p \cdot V = \text{cte}$, $V/T = \text{cte}$), estructura del informe científico (Introducción, Método, Resultados, Conclusión) y difusión en congresos/revistas.

- **Efectos de Audio Nativos (Web Audio API):** Sonidos de acierto, error, racha y fanfarria generados por síntesis web sin necesidad de descargar archivos `.mp3`. Incluye botón para silenciar/activar con guardado de preferencias en `localStorage` (`fiquireto_sound`).
- **Navegación Rápida por Teclado:**
  - Teclas `1`, `2`, `3`, `4` o `A`, `B`, `C`, `D` para responder.
  - Tecla `Enter` o `Espacio` para pasar al siguiente reto.
- **Revisión de Fallos:** Al terminar la partida, los alumnos pueden pulsar en *"Repasar fallos"* para ver qué respondieron, cuál era la opción correcta y leer la explicación detallada.
- **Efecto Confeti:** Animación ligera en canvas al conseguir puntuaciones sobresalientes.



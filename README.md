# Fase 1: Reconocimiento de la necesidad de accesibilidad web

## Objetivo
Comprender la importancia de diseñar webs accesibles y su impacto en los usuarios.

## Tareas

### 1. Investigar sobre la accesibilidad web y redactar un apartado en el informe que responda:

#### ¿Por qué es importante diseñar webs accesibles?
El diseño accesible de sitios web es fundamental para garantizar que todas las personas puedan acceder, navegar e interactuar con el contenido digital. La accesibilidad web no solo beneficia a personas con discapacidades visuales, auditivas, motoras o cognitivas, sino que también mejora la usabilidad general para todos los usuarios.

#### ¿Qué beneficios aporta a los usuarios (especialmente aquellos con discapacidades) y a los desarrolladores?

**Para los Usuarios:**
- Facilita el acceso a la información para personas con discapacidades, promoviendo la inclusión digital.
- Mejora la experiencia del usuario (UX) mediante un diseño claro, estructurado y adaptable.
- Favorece el uso de tecnologías de asistencia como lectores de pantalla, subtítulos o navegación por teclado.

**Para los Desarrolladores y Empresas:**
- Amplía la audiencia potencial al permitir que más usuarios accedan al contenido.
- Cumple con regulaciones y evita sanciones legales.
- Mejora el SEO, ya que los motores de búsqueda favorecen sitios accesibles y bien estructurados.
- Fomenta una imagen corporativa positiva al mostrar compromiso con la inclusión y la responsabilidad social.

#### Relación con normativas vigentes, como las WCAG 2.1 y el Real Decreto 1112/2018.
El diseño accesible está regulado por estándares internacionales y legislaciones específicas. Entre las más relevantes se encuentran:

- **WCAG 2.1 (Web Content Accessibility Guidelines):** Son las pautas internacionales establecidas por el W3C que definen principios y criterios para garantizar la accesibilidad web. Se basan en cuatro principios fundamentales: perceptible, operable, comprensible y robusto.
- **Real Decreto 1112/2018:** Regula la accesibilidad web en España y establece la obligación de cumplir con las WCAG 2.1 en el ámbito público y en ciertas entidades privadas que prestan servicios esenciales.

### 2. Reflexionar sobre cómo la accesibilidad mejora la experiencia del usuario (UX) y contribuye a la inclusión digital.
La accesibilidad mejora la UX al ofrecer sitios web intuitivos, bien estructurados y adaptables a diferentes dispositivos y necesidades. Un diseño accesible no solo elimina barreras para usuarios con discapacidades, sino que también optimiza la navegación para todas las personas, independientemente de su contexto o limitaciones tecnológicas.

# Fase 2: Análisis inicial de accesibilidad en documentos web

## Objetivo
Identificar problemas de accesibilidad en páginas web existentes o en partes del proyecto asignado.

## Tareas

### 1. Seleccionar una página web para analizar.
**Página analizada:** Pennyjuice

### 2. Utilizar herramientas automáticas como WAVE, Lighthouse o TAW para detectar problemas técnicos.
**Herramienta utilizada:** Lighthouse

**Capturas del resultado de la página:**

- **Captura 1:**
  
![image](https://github.com/user-attachments/assets/5b0a7706-0a16-42da-9449-956e50091d74)


- **Captura 2:**
  
![image](https://github.com/user-attachments/assets/52b1838d-8cbe-4097-9803-118d783bbae5)


- **Captura 3 (Accesibilidad):**
  
![image](https://github.com/user-attachments/assets/f7e37a9b-f43d-4fe9-a279-0e203db09e44)


- **Captura 4 (Accesibilidad):**
  
![image](https://github.com/user-attachments/assets/a4ccd68b-bf4e-48a5-a180-e624be44329b)


### 3. Realizar pruebas manuales para verificar aspectos no detectables automáticamente, como etiquetas semánticas correctas o textos alternativos descriptivos.
Se realizaron pruebas manuales para identificar problemas de accesibilidad que no pueden ser detectados automáticamente por Lighthouse. Estas pruebas incluyeron:

- **Verificación de etiquetas semánticas:** Se revisó si la página utiliza correctamente etiquetas estructurales como `<header>`, `<nav>`, `<main>`, `<article>`, `<section>` y `<footer>`. El uso adecuado de estas etiquetas es esencial para que los lectores de pantalla interpreten correctamente la estructura del sitio y faciliten la navegación a personas con discapacidad visual.
  
- **Revisión de textos alternativos en imágenes:** Se comprobó si todas las imágenes cuentan con atributos `alt` descriptivos. Estos textos alternativos son fundamentales para que los usuarios que dependen de lectores de pantalla puedan entender el contenido visual.

- **Evaluación de la navegación por teclado:** Se probó si los elementos interactivos del sitio, como menús, enlaces y botones, pueden ser accedidos utilizando únicamente el teclado (usando las teclas Tab y Enter). Esto es crucial para garantizar que las personas con discapacidades motoras puedan navegar sin depender del mouse.

- **Análisis del contraste de colores:** Se verificó si los textos y los fondos presentan un nivel de contraste suficiente según las pautas WCAG 2.1. Un contraste inadecuado dificulta la lectura, especialmente para personas con baja visión o daltonismo.

- **Revisión del enfoque visible en elementos interactivos:** Se comprobó si los botones y enlaces muestran un indicador visual claro cuando son seleccionados con el teclado, permitiendo a los usuarios saber en qué parte del sitio se encuentran.

### 4. Documentar los problemas encontrados:
Durante las pruebas manuales, se detectaron varios problemas de accesibilidad en la web de PennyJuice:

- **Falta de etiquetas semánticas adecuadas:** La estructura HTML del sitio carece de etiquetas semánticas correctas. Esto dificulta la navegación para personas que utilizan lectores de pantalla, ya que el contenido no está correctamente estructurado y no se identifican claramente las diferentes secciones de la página.

- **Imágenes sin atributo alt descriptivo:** Varias imágenes carecen de un atributo `alt` descriptivo, lo que impide que los usuarios con discapacidad visual comprendan el propósito o contenido de estas imágenes, afectando negativamente su experiencia de navegación.

- **Contraste de colores insuficiente:** Se identificaron combinaciones de colores que no cumplen con los estándares de accesibilidad, lo que dificulta la lectura de ciertos textos, especialmente para personas con problemas de visión.

- **Navegación por teclado limitada:** Algunas secciones del sitio no son accesibles únicamente con el uso del teclado, lo que representa una barrera para los usuarios con discapacidades motoras que no pueden utilizar un mouse.

- **Falta de enfoque visible en botones y enlaces:** Algunos botones y enlaces no presentan un indicador visual claro cuando son seleccionados con el teclado, lo que puede generar confusión, ya que los usuarios no pueden identificar fácilmente qué elemento está seleccionado en cada momento.

# Fase 3: Análisis de principios, pautas y niveles de conformidad

## Principios Fundamentales de las WCAG 2.1

Las **Web Content Accessibility Guidelines (WCAG 2.1)** son un conjunto de directrices diseñadas para hacer que el contenido web sea accesible para todas las personas, especialmente para aquellas con discapacidades. Estas directrices se organizan en cuatro principios fundamentales:

### 1. Perceptible
- **Descripción:** El contenido debe presentarse de manera que los usuarios puedan percibirlo, independientemente de sus capacidades.
- **Pautas relacionadas:**
  - Proporcionar texto alternativo para el contenido no textual: Por ejemplo, imágenes, gráficos y videos deben tener descripciones alternativas en texto para personas con discapacidades visuales.
  - Crear contenido que pueda ser presentado de diferentes formas (por ejemplo, con colores y tamaños ajustables).
  - Asegurar que el contenido multimedia, como videos, tenga subtítulos y transcripciones.
- **Ejemplo práctico:**
  - Agregar un texto alternativo para una imagen: `<img src="foto.jpg" alt="Una niña jugando con un perro en el parque">`.

### 2. Operable
- **Descripción:** Los usuarios deben poder interactuar con el contenido de manera efectiva, utilizando diversas formas de control (por ejemplo, teclado, ratón o dispositivos de asistencia).
- **Pautas relacionadas:**
  - Proporcionar mecanismos de navegación que puedan usarse sin mouse: Esto incluye la navegación por teclado.
  - Asegurar que el contenido no sea programado de manera que sea difícil de usar para personas con discapacidad motora.
  - Dar tiempo suficiente para interactuar con el contenido: Por ejemplo, permitir la pausa o el control de elementos de contenido que se muevan o cambien automáticamente.
- **Ejemplo práctico:**
  - Hacer que todos los botones y enlaces sean accesibles mediante teclado. Ejemplo: utilizar el atributo `tabindex` en los elementos HTML que deseen recibir foco al navegar por el teclado.

### 3. Comprensible
- **Descripción:** El contenido debe ser comprensible para los usuarios, lo que implica que los usuarios deben poder entender el contenido y la interfaz de usuario.
- **Pautas relacionadas:**
  - Utilizar un lenguaje claro y sencillo para facilitar la comprensión del contenido.
  - Hacer que la interfaz de usuario sea predecible: Las acciones y resultados deben ser consistentes en todo el sitio.
  - Proporcionar ayuda en la navegación: Por ejemplo, incluir instrucciones o etiquetas claras en formularios.
- **Ejemplo práctico:**
  - En un formulario de registro, etiquetar claramente los campos, por ejemplo: "Correo electrónico (necesario para recibir confirmaciones)".

### 4. Robusto
- **Descripción:** El contenido debe ser lo suficientemente robusto como para ser interpretado de manera confiable por una amplia variedad de dispositivos, incluidos los dispositivos de asistencia.
- **Pautas relacionadas:**
  - Utilizar tecnologías web estándar: Asegurarse de que el contenido sea compatible con tecnologías actuales y futuras, como navegadores y tecnologías de asistencia.
  - Proporcionar alternativas para los entornos más limitados: Asegurarse de que el contenido sea accesible en diferentes plataformas.
- **Ejemplo práctico:**
  - Usar HTML y CSS válidos que sean reconocidos por todas las plataformas y dispositivos.

## Niveles de Conformidad (A, AA, AAA)

Las **WCAG 2.1** están divididas en tres niveles de conformidad para indicar el grado de accesibilidad alcanzado en un sitio web:

- **Nivel A (Mínimo):** Este nivel cubre las barreras más básicas, sin las cuales el contenido no sería accesible para muchos usuarios.
- **Nivel AA (Intermedio):** Aquí se resuelven las barreras que afectan a una amplia variedad de usuarios. Es el nivel recomendado para alcanzar la accesibilidad mínima aceptable.
- **Nivel AAA (Óptimo):** Este nivel cubre las pautas más avanzadas, dirigidas a usuarios con discapacidades complejas. No es necesario alcanzar este nivel en su totalidad, pero es útil cuando se desea una accesibilidad completa.

## Determinación del Nivel de Conformidad Objetivo (Nivel AA)

### Requisitos del Nivel AA

Este nivel es crucial porque resuelve la mayoría de los problemas de accesibilidad que pueden afectar a los usuarios con discapacidades. Algunos de los requisitos del nivel AA incluyen:

- **Contraste de color suficiente:** El texto debe tener suficiente contraste con el fondo para ser legible por personas con discapacidades visuales.
- **Navegación por teclado:** Todos los elementos interactivos deben ser accesibles mediante teclado.
- **Etiquetas de formulario:** Los campos de formulario deben tener etiquetas claras y visibles, para que los usuarios con discapacidades cognitivas o visuales puedan entenderlos.
- **Evitar contenido que parpadee:** El parpadeo excesivo o los elementos intermitentes deben evitarse para no causar molestias a personas con epilepsia o trastornos neurológicos.

**Ejemplo práctico:**
- **Contraste de color:** Si tienes un botón con texto blanco sobre fondo gris claro, el contraste puede no ser suficiente. Para cumplir con el nivel AA, asegúrate de que el contraste entre el texto y el fondo sea al menos de 4.5:1.
- **Accesibilidad del teclado:** Los menús de navegación deben ser completamente funcionales usando solo el teclado. Por ejemplo, el menú de navegación debe ser navegable usando las teclas de dirección y no depender solo del clic del mouse.

## Aplicación Práctica

Para aplicar las pautas de accesibilidad y alcanzar el nivel AA, puedes implementar lo siguiente:

- **Texto alternativo:** Incluir descripciones de imágenes, iconos y gráficos.
- **Navegación por teclado:** Asegúrate de que todos los elementos interactivos sean accesibles sin mouse, como enlaces, botones y menús.
- **Contraste adecuado:** Usa herramientas como el **Contrast Checker** para asegurarte de que el texto y el fondo tengan un contraste adecuado para personas con baja visión.
- **Etiquetas en formularios:** Usa el atributo `label` en HTML para asociar etiquetas a los campos de entrada.

# Fase 4: Análisis y Priorización de Errores según Puntos de Verificación

## 1. Análisis de los Errores Detectados

### 1. Contraste Insuficiente entre Texto y Fondo
- **Descripción:** Se identificaron combinaciones de colores que no cumplen con los estándares de contraste establecidos por las pautas **WCAG 2.1**. Un contraste insuficiente dificulta la lectura, especialmente para personas con baja visión o daltonismo.

### 2. Imágenes sin Texto Alternativo
- **Descripción:** Varias imágenes en la página carecen de un atributo `alt` descriptivo, lo que impide que los usuarios con discapacidad visual comprendan el contenido o propósito de estas imágenes.

### 3. Formularios sin Etiquetas Descriptivas
- **Descripción:** En algunos formularios, las etiquetas descriptivas están ausentes o mal implementadas. Las etiquetas son necesarias para que los usuarios que utilizan lectores de pantalla comprendan el propósito de cada campo en un formulario.

### 4. Navegación por Teclado Limitada
- **Descripción:** Algunas secciones del sitio no son accesibles solo con el uso del teclado, lo que representa una barrera para los usuarios con discapacidades motoras que no pueden utilizar un mouse.

### 5. Falta de Enfoque Visible en Elementos Interactivos
- **Descripción:** Algunos botones y enlaces no muestran un enfoque visual claro al ser seleccionados mediante el teclado, lo que genera confusión sobre qué elemento está activo.

## 2. Priorización de Errores según su Impacto

### 1. Alta Prioridad:
- **Imágenes sin texto alternativo:** Este problema afecta de manera significativa a la accesibilidad y comprensión de contenido para usuarios con discapacidad visual. No proporcionar texto alternativo impide que los usuarios con lectores de pantalla comprendan la información visual, lo que puede llevar a una experiencia completamente inaccesible.
- **Navegación por teclado limitada:** La imposibilidad de navegar solo con el teclado afecta gravemente a los usuarios con discapacidades motoras. Este problema debe ser corregido de inmediato para garantizar que todos los usuarios puedan acceder a todas las funciones del sitio.

### 2. Media Prioridad:
- **Contraste insuficiente entre texto y fondo:** Aunque no es tan crítico como los problemas anteriores, un contraste insuficiente puede causar dificultades en la lectura para personas con baja visión o daltonismo. Corregirlo mejorará la experiencia de un grupo significativo de usuarios.
- **Falta de enfoque visible en elementos interactivos:** Aunque no es tan grave como los problemas mencionados anteriormente, la falta de un enfoque visible dificulta la navegación y puede generar frustración, especialmente para personas con discapacidades visuales o motoras.

### 3. Baja Prioridad:
- **Formularios sin etiquetas descriptivas:** Aunque este problema debe ser corregido, su impacto es algo limitado en comparación con los problemas de navegación o contenido visual. Sin embargo, sigue siendo crucial para garantizar que los usuarios comprendan qué se requiere en cada campo del formulario.

## 3. Soluciones Propuestas

### 1. Contraste Insuficiente entre Texto y Fondo
- **Solución:** Ajustar los colores de fondo y texto para cumplir con las pautas de contraste mínimo de **WCAG 2.1**. Se recomienda utilizar herramientas automáticas de comprobación de contraste.

### 2. Imágenes sin Texto Alternativo
- **Solución:** Asegurarse de que todas las imágenes en el sitio tengan un atributo `alt` descriptivo que resuma el contenido y propósito de cada imagen. Esto permitirá que los usuarios de lectores de pantalla comprendan las imágenes y su contexto en el sitio.

### 3. Formularios sin Etiquetas Descriptivas
- **Solución:** Añadir etiquetas descriptivas a cada campo de formulario utilizando elementos `<label>` en **HTML**, asegurándose de que cada campo tenga una descripción clara de lo que se debe ingresar.

### 4. Navegación por Teclado Limitada
- **Solución:** Asegurarse de que todos los elementos interactivos del sitio sean accesibles solo con el teclado. Se debe utilizar la tecla `Tab` para navegar entre los elementos interactivos, y la tecla `Enter` para activarlos.

### 5. Falta de Enfoque Visible en Elementos Interactivos
- **Solución:** Implementar un enfoque visual claro (por ejemplo, un borde resaltado o cambio de color) para los botones y enlaces cuando se navega por teclado. Esto permitirá a los usuarios saber qué elemento está activo y facilita la navegación.

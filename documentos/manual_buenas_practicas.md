# Manual de Buenas Prácticas para Trabajos Universitarios en Grupo

**Autores:** Juan Rosales y Víctor Materán  
**Institución:** Universidad Valle del Momboy (UVM) — Facultad de Ingeniería  
**Versión:** 1.0  

---


## 1. Organización y Roles del Equipo

El éxito de un proyecto universitario en grupo depende de definir responsabilidades claras desde la primera reunión, evitando duplicidad de esfuerzos o tareas sin dueño.

### 1.1 Roles Recomendados en Equipos Académicos
| Rol | Responsabilidades Principales |
| :--- | :--- |
| **Coordinador de Proyecto** | Supervisa el cumplimiento del cronograma, convoca reuniones breves de seguimiento y verifica que cada sección responda a la rúbrica de evaluación. |
| **Redactor Técnico** | Desarrolla el contenido central asignado con coherencia, rigurosidad conceptual y respaldo bibliográfico verificable. |
| **Revisor de Estilo y Normativa** | Unifica la redacción en tercera persona, corrige ortografía, verifica márgenes, numeración de tablas/figuras y aplica Normas APA. |
| **Gestor de Repositorio y Presentación** | Administra el control de versiones en GitHub, consolida el documento final en PDF y estructura las diapositivas para la defensa oral. |

*(Nota: En equipos de dos integrantes, cada miembro asume de forma equilibrada la redacción de la mitad del documento y actúa como revisor cruzado del trabajo de su compañero).*

### 1.2 Acuerdos Iniciales de Convivencia
* Establecer un canal oficial de comunicación (WhatsApp, Telegram o Discord) y un horario fijo para revisiones rápidas.
* Definir un tiempo máximo de respuesta (por ejemplo, 12 horas) ante consultas o solicitudes de revisión en GitHub.
* Acordar desde el inicio el formato de entrega y la distribución equitativa de páginas o secciones.

---

## 2. Gestión de Tiempos y Planificación

Dejar la integración del documento para las últimas horas antes de la entrega es la principal causa de errores de formato e incoherencias. Se recomienda aplicar **planificación inversa** a partir de la fecha límite establecida por el docente.

### 2.1 Distribución Sugerida del Tiempo Total (100 %)
1. **Planificación y reparto de tareas (15 %):** Lectura de la rúbrica, creación del repositorio, apertura de Issues y asignación de secciones.
2. **Investigación y redacción de borradores (45 %):** Búsqueda de fuentes confiables y desarrollo individual de cada sección en su rama correspondiente.
3. **Revisión cruzada e integración (25 %):** Apertura de Pull Requests, comentarios de mejora entre compañeros, resolución de conflictos y unificación de estilo.
4. **Control de calidad y exportación final (15 %):** Revisión final de tablas, figuras, índice, referencias APA, generación del PDF y preparación de la defensa.

### 2.2 Buenas Prácticas de Seguimiento
* Dividir el trabajo en entregables pequeños (hitos cada 2 o 3 días) reflejados en un tablero Kanban (*Por hacer*, *En progreso*, *Finalizado*).
* Establecer un **cierre interno de redacción** al menos 48 horas antes de la entrega oficial para dedicar ese margen exclusivamente a revisión y formato.

---

## 3. Herramientas Colaborativas y Control de Versiones

Trabajar enviando archivos por mensajería con nombres como `Trabajo_Final_v2_ahora_si.docx` genera pérdida de información y confusión. El uso combinado de plataformas en la nube y control de versiones resuelve este problema.

### 3.1 Ecosistema Recomendado
* **GitHub (Control de versiones y gestión):** Centraliza el historial de cambios, asigna tareas mediante *Issues*, organiza el avance en *Projects (Kanban)* y valida cada aporte antes de integrarlo a la versión principal (`main`).
* **Google Docs / Word (Edición auxiliar):** Útil para borradores rápidos o exportación final a PDF cuando se requieren plantillas institucionales específicas.
* **Markdown (`.md`):** Formato ligero de texto plano ideal para documentación en GitHub, ya que permite visualizar exactamente qué líneas se agregaron o modificaron en cada revisión.

### 3.2 Flujo Colaborativo en GitHub (Sin Programación)
1. **Ramas independientes:** Cada estudiante edita su sección en una rama propia para no alterar la versión estable (`main`).
2. **Commits descriptivos:** Guardar cambios frecuentes con mensajes claros que expliquen qué se hizo (ejemplo: *Añade tabla de distribución de tiempos en sección 2*).
3. **Pull Requests (PR) y revisión por pares:** Antes de fusionar una rama con `main`, el compañero revisa el texto, sugiere correcciones en los comentarios y aprueba la integración.
4. **Resolución de conflictos:** Si dos integrantes editan la misma línea de un archivo, GitHub señala el conflicto (`<<<<<<<`, `=======`, `>>>>>>>`) para decidir qué versión conservar de forma manual y limpia antes de finalizar la fusión.
5. **Etiquetado de versiones (`Tags` y `CHANGELOG.md`):** Cada hito consolidado se etiqueta (`v1.0` para la primera versión completa, `v1.1` para ajustes tras revisión) documentando los cambios en `CHANGELOG.md`.
 main




 feature/formatos-citacion-presentacion
## 4. Formatos Académicos y Estilo de Redacción

Un documento universitario en grupo debe leerse como una obra escrita por un solo autor, manteniendo uniformidad visual y lingüística en todas sus páginas.

### 4.1 Estándares de Presentación Documental
* **Tipografía y tamaño:** Times New Roman 12 pt o Arial/Calibri 11 pt de forma uniforme en todo el cuerpo del texto.
* **Interlineado y alineación:** Interlineado de 1,5 líneas (o doble según exigencia de la cátedra), alineación justificada o a la izquierda sin espacios irregulares entre párrafos.
* **Márgenes:** 2,54 cm (1 pulgada) en los cuatro bordes de la página (o 3 cm izquierdo / 2,5 cm restantes según normativa de facultad).
* **Jerarquía de títulos:** Usar niveles claros (`#` Título principal, `##` Capítulo o sección, `###` Subsección) evitando abusar de mayúsculas sostenidas o negritas innecesarias dentro de los párrafos.
* **Tablas y figuras:** Numerarlas de forma correlativa (*Tabla 1*, *Tabla 2*; *Figura 1*, *Figura 2*) con título descriptivo en la parte superior y nota de fuente en la parte inferior (*Fuente: Elaboración propia, 2026*).

### 4.2 Estilo de Redacción Técnica
* Redactar en **tercera persona impersonal** (*"Se analizó..."*, *"El presente estudio propone..."*) evitando expresiones coloquiales o en primera persona singular.
* Definir las siglas la primera vez que aparecen en el texto: por ejemplo, *Control de Versiones (CV)* o *Normas de la Asociación Americana de Psicología (APA)*.
* Preferir párrafos concisos de entre 4 y 7 líneas con conectores lógicos adecuados.

---

## 5. Citación y Referencias Bibliográficas (Normas APA 7.ª Edición)

Todo dato, concepto o metodología tomada de otros autores debe acreditarse correctamente para garantizar el rigor académico y evitar el plagio.

### 5.1 Tipos de Citas en el Texto
* **Cita parafraseada (recomendada):** Se expresa la idea del autor con palabras propias manteniendo el sentido original.  
  *Ejemplo:* Según Chacon y Straub (2020), el control de versiones distribuido facilita la trazabilidad documental en equipos multidisciplinarios.
* **Cita textual corta (menos de 40 palabras):** Se incorpora dentro del párrafo entre comillas dobles indicando autor, año y número de página.  
  *Ejemplo:* "La gestión estructurada de repositorios reduce los errores de integración en proyectos colaborativos" (Pérez, 2023, p. 45).
* **Cita textual larga (40 palabras o más):** Se escribe en un bloque independiente con sangría izquierda de 1,27 cm, sin comillas y con el punto final antes del paréntesis de la fuente.

### 5.2 Lista de Referencias
* Se ubica al final del documento ordenada alfabéticamente por el apellido del primer autor y con **sangría francesa** (1,27 cm).
* Todo autor citado en el cuerpo del texto debe aparecer en la lista de referencias y viceversa. *(Ver guía ampliada en `referencias/guia_apa_7ma_edicion.md`)*.


---

## 6. Presentación Escrita y Defensa Oral en Grupo

La etapa final convierte el trabajo técnico en un entregable profesional listo para evaluación académica.

### 6.1 Checklist de Control de Calidad (Antes de Exportar a PDF)
- [ ] **Portada institucional:** Incluye logo universitario, facultad, escuela, título del proyecto, integrantes, docente, lugar y año.
- [ ] **Índices actualizados:** Índice general, índice de tablas e índice de figuras coinciden exactamente con la numeración de páginas.
- [ ] **Integridad visual:** Ninguna tabla o título queda cortado al final de una página; todas las imágenes tienen buena resolución.
- [ ] **Coherencia de citas:** Todas las fuentes mencionadas están completas en la sección de referencias.
- [ ] **Exportación limpia:** El archivo PDF final se revisó página por página antes de subirlo al aula virtual o repositorio.

### 6.2 Buenas Prácticas para la Defensa Oral
* **Diapositivas ejecutivas:** Aplicar la regla de síntesis visual (máximo 5 a 6 líneas por lámina, priorizando esquemas, tablas resumen y diagramas sobre bloques largos de texto).
* **Distribución equitativa:** Asignar tiempos claros a cada expositor (por ejemplo, 5 minutos por integrante) y ensayar las transiciones entre compañeros.
* **Dominio integral:** Aunque cada integrante haya redactado secciones específicas, todo el equipo debe conocer el contenido completo del manual para responder con solvencia a las preguntas del jurado o docente.


Co-authored-by: Víctor Materán


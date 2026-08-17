# PROY01 · Proyecto 1

> Primer proyecto en la tarjeta Zybo Z7, con foco en VHDL. Se desarrolla en grupo y se evalúa con un informe, un video y el proyecto implementado en la tarjeta.

El proyecto consiste en plantear e implementar una idea propia y coherente que abarque **10 actividades**: 3 obligatorias (AO1–AO3) y 7 complementarias (AC1–AC7). Las obligatorias son el mínimo para aprobar; las complementarias son las que permiten optar al 7,0. Todo el detalle está en el enunciado.

---

## 📋 Enunciado y entrega

| Documento | Descripción |
| :--- | :--- |
| [Enunciado del proyecto](https://github.com/IEE2463-SEP/PROY01/blob/HEAD/Proyecto_01_IEE2463.pdf) | Las 10 actividades, el cumplimiento ético, el formato de entrega y la rúbrica de evaluación. **Léalo completo antes de empezar.** |
| [Plantilla del informe](https://github.com/IEE2463-SEP/PROY01/blob/HEAD/Informe_Proyecto_1_SEP.zip) | Plantilla LaTeX (formato IEEE Access) para subir a Overleaf. Trae las secciones fijas del informe, el puntaje de cada una y un mini tutorial de LaTeX. |
| [Penalización por entrega atrasada](https://github.com/IEE2463-SEP/PROY01/blob/HEAD/Penalizaci%C3%B3n_Entregas_Proyecto.pdf) | Cómo baja la nota si entrega fuera de plazo: descuento de 0,1 cada 6 minutos durante las 2 primeras horas, y decaimiento cuadrático hasta 1,0 a las 12 horas. |

La entrega es **un solo PDF en Canvas** con tres links: informe, video y un `.zip` con el proyecto de Vivado/Vitis. Subir más de 3 archivos, con nombres o formato incorrectos, **penaliza la nota final con 1 punto**.

---

## 🧩 El diagrama del proyecto

El **diagrama** es un entregable por sí mismo: vale el **50 % de la nota de avance del proyecto**, por encima de cada actividad obligatoria (25 % cada una). No es un dibujo decorativo — es donde usted demuestra que sabe qué va a construir antes de construirlo.

Para que valga nota 7,0 el diagrama debe estar hecho de forma prolija en un software, indicar sobre cada flecha **qué datos se transaccionan entre bloques**, y marcar con colores **dónde se cumple cada una de las 10 actividades**.

| Documento | Descripción |
| :--- | :--- |
| [Diagramas de ejemplo](https://github.com/IEE2463-SEP/PROY01/blob/HEAD/diagramas_proyecto_1.pdf) | Ejemplo real de un proyecto de un semestre anterior, usado como referencia del estándar esperado. |

Ese archivo es el diagrama de *El Para Cronómetro Inador*, un juego de reflejos con niveles de dificultad desarrollado por el Grupo 19 de un semestre anterior. Está organizado así:

- **Diagrama de bloques con insignias** (p. 1) — la arquitectura completa, con una insignia sobre cada bloque indicando qué actividad se cumple ahí: `AO2 1/3` significa "una de las tres partes con que se cumple la AO2". Esto es exactamente lo que pide la rúbrica.
- **Portada** (p. 2) — nombre del proyecto y grupo.
- **Máquina de estados** (p. 3) — los estados S0 a S4 con las transiciones por botón y qué muestran los LEDs en cada uno. Es la vista de comportamiento, complementaria a la de bloques.
- **Segunda versión del diagrama de bloques** (p. 4) — sin insignias y con la memoria organizada distinto (dos *Memory Managers* y una BRAM *Simple Dual Port*). Sirve para ver que el diagrama se rehace a medida que el proyecto evoluciona.
- **Checklist de las 10 actividades** (p. 5) — con ✓ las logradas y con `+/-` las parcialmente logradas. Note que el grupo marcó AC3 y AC6 como parciales: se espera honestidad, no inflar el cumplimiento.
- **Una lámina por actividad** (p. 6 en adelante) — la evidencia concreta de cada AO y AC: el fragmento de código, el *block design* o la captura de ILA/VIO que la demuestra.

**Úselo como referencia de formato y nivel de detalle, no como plantilla a copiar.** La idea del proyecto debe ser de su autoría, y cualquier elemento tomado de otra fuente debe quedar referenciado.

---

## 📊 Evaluación

La nota del proyecto se compone de la **entrega final** y del **avance**.

| Entrega final | Peso | Dónde está el detalle |
| :--- | :--- | :--- |
| Informe | 35 % | [Plantilla del informe](https://github.com/IEE2463-SEP/PROY01/blob/HEAD/Informe_Proyecto_1_SEP.zip) — cada sección indica su puntaje |
| Video | 35 % | [Enunciado](https://github.com/IEE2463-SEP/PROY01/blob/HEAD/Proyecto_01_IEE2463.pdf), sección 4.2. Entre 5 y 15 min; sobre 15 min no se revisa |
| Códigos | 30 % | [Enunciado](https://github.com/IEE2463-SEP/PROY01/blob/HEAD/Proyecto_01_IEE2463.pdf), sección 4.3 |

| Avance | Descripción |
| :--- | :--- |
| [Rúbrica de avance](https://github.com/IEE2463-SEP/PROY01/blob/HEAD/Rubrica_Avance_Proyecto_01_IEE2463_.pdf) | Evaluación formal de avance (50 % diagrama + 25 % AO + 25 % AO) y las jornadas de avance semanal PROG01–PROG04, donde se llama al azar a 3–5 grupos. |

---

## 🗂️ Proyectos de ejemplo

Dos proyectos completos de semestres anteriores, con informe, video, código y proyecto de Vivado:

| Repositorio | Proyecto |
| :--- | :--- |
| [PROY01-Ejemplo1](https://github.com/IEE2463-SEP/PROY01-Ejemplo1) | Juego de la Vida de Conway |
| [PROY01-Ejemplo2](https://github.com/IEE2463-SEP/PROY01-Ejemplo2) | Conversor de hora UTC |

---

## ❓ Dudas

Cualquier duda asociada al proyecto debe ser subida como un *issue* en este repositorio.

Mucho éxito en el desarrollo del proyecto.

---

<sub>IEE2463 · Sistemas Electrónicos Programables</sub>

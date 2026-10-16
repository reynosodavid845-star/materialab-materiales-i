# Supuestos, inconsistencias y decisiones

## Decisiones de contenido

- Los valores evaluables se muestran tal como aparecen en las diapositivas, aun cuando difieren de valores de otros textos.
- Los diagramas interactivos son esquemáticos y se identifican expresamente como aproximados. Sirven para practicar el procedimiento, no para obtener una lectura metrológica.
- El constructor Fe-C usa reglas didácticas por regiones amplias. Cuando una frontera depende de la curva exacta, indica que se consulte el diagrama original.
- “Fase” y “microconstituyente” se presentan como categorías diferentes en todos los resultados.
- La aplicación no tiene backend; el progreso, las respuestas y el estado de las tarjetas se guardan en `localStorage` del navegador.

## Inconsistencias detectadas

1. **Regla de la palanca:** Clase 10, p. 32 muestra `W_L = 72.7%` y `W_α = 23.3%`. Con C_L=32, C_0=35 y C_α=43, la fórmula de la p. 31 produce `W_α = 27.3%` y el balance suma 100%. La calculadora usa el resultado matemáticamente consistente y muestra la advertencia.
2. **Estabilidad de la ledeburita:** Clase 11, p. 20 indica estabilidad hasta 723 °C; la p. 28 indica hasta 1130 °C. La aplicación no oculta la discrepancia y evita usarla como frontera exacta.
3. **Rango de fundiciones:** Clase 11, p. 9 presenta 2.11–6.11% C; Clase 16, p. 9 presenta 2.11–4.3% C. En los comparadores se prioriza la clasificación contextual de Clase 16 y se conserva la nota de conflicto.
4. **Valores Fe-C del curso:** Clase 11, p. 26 usa 1492 °C/0.4%C para el peritéctico, 1130 °C/4.3%C para el eutéctico y 723 °C/0.89%C para el eutectoide. La hoja de fórmulas conserva esos valores, en vez de sustituirlos por cifras externas.

## Alcance del tutor

El tutor es una recuperación local basada en un índice curado de conceptos. No llama a servicios externos ni inventa respuestas: cuando no encuentra respaldo, declara que la pregunta queda fuera del alcance indexado.

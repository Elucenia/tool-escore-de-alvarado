<!-- ELUCENIA technical documentation · escore-de-alvarado · es · no clinical/professional/rights approval -->

# Puntuación de Alvarado

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escore-de-alvarado)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Migración del dolor a la fosa ilíaca derecha

`migra`

### Anorexia (o acetona en la orina)

`anorex`

### Náuseas o vómitos

`nausea`

### Dolor a la palpación de la fosa ilíaca derecha

`dor`

### Dolor a la descompresión brusca (signo de Blumberg)

`desc`

### Temperatura ≥ 37,3 °C

`febre`

### Leucocitosis \> 10.000/mm³

`leuco`

### Desviación a la izquierda (neutrófilos \> 75%)

`desvio`

## Edición del método

Alvarado 1986: MANTRELS 8 ítems, 0–10; versión con desviación izquierda

## Fórmula documentada

MANTRELS: Migración (1), Anorexia (1), Náuseas/vómitos (1), T dolor en fosa ilíaca derecha (2), R rebote doloroso (1), Elevación de temperatura (1), Leucocitosis (2), S desviación izquierda (1). Total 0 a 10.

## Límites y población

El Alvarado 1986 se elaboró a partir de 305 pacientes hospitalizados con dolor abdominal sugestivo de apendicitis y ocho factores clínicos/de laboratorio. El resumen original no valida automáticamente distintos grupos de edad, embarazadas ni estrategias de alta/imagen. Los umbrales de decisión y la población de la versión utilizada deben comprobarse por separado; la herramienta implementa la variante que incluye desviación a la izquierda.

## Referencias

- [Alvarado A. A practical score for the early diagnosis of acute appendicitis. Ann Emerg Med, 1986.](https://doi.org/10.1016/S0196-0644(86)80993-3)

- [Di Saverio S et al. Diagnosis and treatment of acute appendicitis: 2020 update of the WSES Jerusalem guidelines. World J Emerg Surg, 2020.](https://doi.org/10.1186/s13017-020-00306-3)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

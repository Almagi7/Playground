# Reporte de Evaluaciones 5S

Este proyecto utiliza Google Apps Script para generar reportes en Google Docs a partir de respuestas de formularios almacenadas en Google Sheets. Cada reporte incluye calificaciones, comentarios y evidencia fotográfica para trece personas.

## Descripción

El script lee los datos de una hoja de cálculo de Google Sheets y genera un documento de Google Docs con un reporte para cada persona. Cada reporte incluye:

- Área
- Evaluador
- Calificación promedio de las 5S
- Fecha
- Responsable
- Comentarios numerados
- Evidencia fotográfica

## Estructura de la Hoja de Cálculo

La hoja de cálculo debe tener la siguiente estructura:

1. Marca temporal (ignorada por el script)
2. Fecha
3. Evaluador
4. Calificación de la 1ra S de la Persona 1
5. Comentario de la 1ra S de la Persona 1
6. Calificación de la 2da S de la Persona 1
7. Comentario de la 2da S de la Persona 1
8. Calificación de la 3ra S de la Persona 1
9. Comentario de la 3ra S de la Persona 1
10. Calificación de la 4ta S de la Persona 1
11. Comentario de la 4ta S de la Persona 1
12. Calificación de la 5ta S de la Persona 1
13. Comentario de la 5ta S de la Persona 1
14. Evidencia fotográfica de la Persona 1
15. Calificación de la 1ra S de la Persona 2
16. Comentario de la 1ra S de la Persona 2
17. ... (y así sucesivamente para las 13 personas)

## Uso

1. Abre el script en el editor de Google Apps Script.
2. Cambia el ID del documento de Google Docs en la variable `docId` por el ID de tu documento.
3. Asegúrate de que la hoja de cálculo tenga el nombre `Respuestas de formulario 1`.
4. Ejecuta la función `onFormSubmit` para generar los reportes.
____________________________________________________________________________________________________________________
# 5S Evaluation Report

This project uses Google Apps Script to generate reports in Google Docs from form responses stored in Google Sheets. Each report includes ratings, comments, and photographic evidence for thirteen people.

## Description

The script reads data from a Google Sheets spreadsheet and generates a Google Docs document with a report for each person. Each report includes:

- Area
- Evaluator
- Average 5S rating
- Date
- Responsible person
- Numbered comments
- Photographic evidence

## Spreadsheet Structure

The spreadsheet should have the following structure:

1. Timestamp (ignored by the script)
2. Date
3. Evaluator
4. Rating of the 1st S for Person 1
5. Comment on the 1st S for Person 1
6. Rating of the 2nd S for Person 1
7. Comment on the 2nd S for Person 1
8. Rating of the 3rd S for Person 1
9. Comment on the 3rd S for Person 1
10. Rating of the 4th S for Person 1
11. Comment on the 4th S for Person 1
12. Rating of the 5th S for Person 1
13. Comment on the 5th S for Person 1
14. Photographic evidence for Person 1
15. Rating of the 1st S for Person 2
16. Comment on the 1st S for Person 2
17. ... (and so on for the 13 people)

## Usage

1. Open the script in the Google Apps Script editor.
2. Change the ID of the Google Docs document in the `docId` variable to the ID of your document.
3. Ensure that the spreadsheet is named `Respuestas de formulario 1`.
4. Run the `onFormSubmit` function to generate the reports.


# bayesian_analysis
Repositorio para notas de estadística bayesiana

## Comandos de Bash

Convertir archivo `<file>.dat` en archivos `<file>.csv`:

>cat <input_file>.dat | awk 'BEGIN {OFS=","} NR>1 {print $1, $2, $3, $4, $5, $6, $7}' > <output_file>.csv

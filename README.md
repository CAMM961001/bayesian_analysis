# bayesian_analysis
Repositorio para notas de estadística bayesiana

## Comandos de Bash

Convertir archivo `<file>.dat` en archivos `<file>.csv`:

>cat <file.dat> | sed 's/ //g' | grep -v '^$' > <output_file>.csv

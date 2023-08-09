# bayesian_analysis
Repositorio para notas de estadística bayesiana

## Comandos de Bash

Convertir archivo `<file>.dat` en archivos `<file>.csv`:

* Primero es necesario instalar la librería de Python csvkit: `sudo pip install csvkit`
* Verificar instalación: `csvformat -h`
* Convertir archivo: `csvformat input.dat -S -d ' ' > output.csv`

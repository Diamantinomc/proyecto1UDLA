# Proyecto: Packing de Cerezas

## Descripción
Este proyecto está orientado al análisis, visualización y desarrollo de una aplicación en R para el proceso de packing de cerezas, con énfasis en el reconocimiento de variables que oinfluyan en la calidad del fruto. Incluye documentos exploratorios, presentaciones, reportes en PDF y una aplicación interactiva.

# Estructura del proyecto

packing_cerezas/

├── R/                                  # Scripts con funciones personalizadas en R

│   └── plot_temps.R

│
├── data/                               # Archivos de datos utilizados en los análisis

│   ├── packing_cerezas.csv

│   └── state_medians.csv

│
├── colors_app_files/libs/              # Recursos estáticos generados por Quarto

│   ├── bootstrap/                      # Estilos y scripts de Bootstrap

│   ├── clipboard/                      # Funcionalidad de copiado

│   └── quarto-html/                    # Scripts y estilos de Quarto para HTML

│
├── packing_cereza_files/figure-pdf/    # Figuras generadas durante el renderizado

│   ├── unnamed-chunk-10-1.pdf

│   ├── unnamed-chunk-10-2.pdf

│   └── unnamed-chunk-13-1.pdf

│
├── colors_app.qmd                      # Código fuente de la aplicación interactiva

├── colors_app.html                     # Versión HTML renderizada de la app

├── colors_document.qmd                 # Documento técnico con análisis detallado

├── colors_presentation.qmd             # Presentación (revealjs)

├── packing_cereza.qmd                  # Análisis principal del proceso de packing

├── packing_cereza.pdf                  # Informe final en PDF

├── README.qmd                          # Versión Quarto del README

├── README.md                           # Versión Markdown del README

└── project.Rproj                       # Archivo de proyecto para RStudio



## Cómo comenzar

1. Clona este repositorio:
git clone https://github.com/tu-usuario/packing_cerezas.git

2. Abre el archivo project.Rproj en RStudio.

3. Asegúrate de tener las dependencias instaladas:
install.packages(c("tidyverse", "quarto", "shiny", "ggplot2", "dplyr", ...))

4. Para ejecutar la app interactiva:
quarto::quarto_preview("colors_app.qmd")

## Documentos incluidos
colors_app.qmd: App interactiva para visualizar datos por color.

colors_document.qmd: Documento técnico con análisis detallado.

colors_presentation.qmd: Presentación en formato HTML.

packing_cereza.qmd: Documento central del proyecto con análisis completos.

packing_cereza.pdf: Versión en PDF del informe final.

## Tecnologías utilizadas
Lenguaje: R

Visualización: ggplot2, Quarto

App interactiva: Shiny + Quarto

Documentación: Quarto (QMD → HTML/PDF/Revealjs)

## Autor
Nombre: Adán Marchena Romero

Email: adan.marchena@hotmail.com

Universidad de las Américas


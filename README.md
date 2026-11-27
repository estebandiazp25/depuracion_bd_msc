# 🧬 Depuración y análisis de bases de datos microbiológicas

Repositorio de scripts desarrollados en **R** para la integración, estandarización, depuración y análisis de bases de datos microbiológicas provenientes de sistemas de información de laboratorio clínico.

El proyecto reúne herramientas para automatizar procesos de limpieza de datos, homologación de variables, clasificación de microorganismos y generación de resultados estadísticos y gráficos. Incluye procedimientos específicos para la caracterización de **Bacilos Gram Negativos No Fermentadores (BGNNF)**.

## 📂 Scripts disponibles

Los scripts se encuentran organizados según las diferentes etapas del procesamiento de la información.

### 1. Integración de bases de datos
Unión de múltiples bases de datos en una estructura consolidada para facilitar el procesamiento y análisis de la información.

- **Código:** [unir_bd](https://gist.github.com/estebandiazp25/34d73f74818d0c55bf47c2375419fb7f#file-unir_bd-txt)

### 2. Depuración de registros duplicados
Identificación y eliminación de registros duplicados para mejorar la integridad y consistencia de la información.

- **Código:** [desduplicar](https://gist.github.com/estebandiazp25/34d73f74818d0c55bf47c2375419fb7f#file-desduplicar-txt)

### 3. Generación de catálogo de microorganismos
Identificación, organización y generación de un catálogo único de microorganismos presentes en las bases de datos.

- **Código:** [catalogo_mo](https://gist.github.com/estebandiazp25/34d73f74818d0c55bf47c2375419fb7f#file-catalogo_mo-txt)

### 4. Homologación de variables
Estandarización y equivalencia de las variables relacionadas con los servicios y los tipos de muestra, permitiendo unificar diferentes denominaciones.

- **Código:** [equivalencias](https://gist.github.com/estebandiazp25/34d73f74818d0c55bf47c2375419fb7f#file-equivalencias-txt)

### 5. Depuración y clasificación de microorganismos, Análisis descriptivo, Visualización de datos
Depuración de la base de datos según el tipo de microorganismo de interés. Incluye criterios de clasificación específicos para el estudio de Bacilos Gram Negativos No Fermentadores (BGNNF).
 
Procesamiento y resumen estadístico de la información para caracterizar los registros microbiológicos y obtener indicadores descriptivos.

Generación de gráficos para representar los resultados y facilitar la interpretación de los datos microbiológicos.

- **Código:** [depuracion_estadistica](https://gist.github.com/estebandiazp25/34d73f74818d0c55bf47c2375419fb7f#file-depuracion_estadistica-txt)

---

## 🛠️ Tecnologías y herramientas

- **Lenguaje:** R
- **Entorno de desarrollo:** RStudio
- **Procesamiento de datos:** dplyr
- **Importación de archivos:** readxl
- **Exportación de archivos:** writexl
- **Visualización:** ggplot2

## 🎯 Objetivo

Facilitar la gestión, estandarización y análisis de bases de datos microbiológicas mediante herramientas reproducibles en R, contribuyendo a mejorar la calidad de los datos y optimizar los procesos de investigación y vigilancia microbiológica.

---

**Autor:** Esteban Díaz

**Repositorio:** depuracion_bd_msc

**Lenguaje principal:** R

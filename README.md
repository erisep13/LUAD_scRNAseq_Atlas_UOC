# Generación de un atlas de scRNA-seq de adenocarcinoma de pulmón con mutaciones driver en EGFR

## Resumen del proyecto

Este repositorio presenta la construcción de un atlas transcriptómico de célula única de 
pacientes con adenocarcinoma de pulmón (LUAD), profundizando en aquellos tumores 
producidos por una mutación driver en el gen del receptor del factor de crecimiento 
epidérmico (EGFR). Para la construcción del atlas, así como para la caracterización 
celular del microambiente tumoral se utiliza principalmente el paquete de Seurat para 
R, así como los paquetes ProjecTILs y Monocle para analizar las trayectorias de grupos 
celulares de interés. El objetivo de este estudio es determinar las poblaciones celulares 
propias presentes en los pacientes de interés estableciendo una comparación con 
pacientes cuyo gen driver es *KRAS*, entre los diferentes tipos de mutación en *EGFR* 
registrados, y una comparación dependiente del sexo de los pacientes. Los resultados 
obtenidos muestran la gran heterogeneidad del microambiente tumoral y sutiles 
cambios en las proporciones de las poblaciones de células inmunitarias y células 
cancerígenas. Asimismo, se describen estrategias inmunitarias diferenciales entre 
mujeres y hombres que se alinean con evidencia previa sobre el efecto de esta 
enfermedad dependiente del sexo.

## Adquisición de los datos de origen

El dataset de referencia procede del estudio [Prazanowska, K. H. & Lim, S. B. (2023)](https://doi.org/10.1038/s41597-023-02074-6) y el objeto Seurat producto de este se puede acceder desde [*figshare*](https://doi.org/10.6084/m9.figshare.c.6222221.v3). El dataset de validación procede del estudio [Maynard, A., *et al*. (2020)](https://doi.org/10.1016/j.cell.2020.07.017) accedidos desde su repositorio de [GitHub](https://github.com/czbiohub-sf/scell_lung_adenocarcinoma/tree/master?tab=readme-ov-file).

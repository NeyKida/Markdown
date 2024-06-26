# Describir datos de manera consistente 
## ¿Qué son los metadados?
En [este corto video](https://embl-ebi.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=4ae906db-607b-4d3f-9a90-acf700d16eca&start=0), Sarah Morgan, Coordinadora de Formación Científica en EMBL-EBI,
habla sobre qué es el metadato y por qué es importante hacer un seguimiento de esta 
información en experimentos biológicos.

## La importancia de los metadatos
Para que los datos sean útiles, es necesario contextualizarlos. Una manera de hacer esto
es asociarlos con **metadatos** - básicamente son datos sobre los datos mismos. Si estás 
interesado en secuenciar muestras del medio ambiente, quizá para entender la biodiversidad 
en diferentes condiciones, o para investigar asociaciones entre el rendimiento de los cultivos 
y las diferencias en la flora del suelo, sería útil, por ejemplo, saber cuándo y dónde se
recolectaron tus muestras. Descripciones estandarizadas del momento de recolección y la ubicación
geográfica pueden asociarse con cualquier secuencia derivada de cada muestra. Los metadatos son
tan importantes que existen bases de datos dedicadas a organizarlos. Por ejemplo, la [base de
datos de BioSamples](https://www.ebi.ac.uk/biosamples/) contiene metadatos sobre muestras 
utilizadas para generar datos almacenados en ENA, PRIDE y ArrayExpress. Almacenar los metadatos
de esta manera asegura que al citar una muestra específica se haga de manera consistente en varios recursos de datos.

Imaginemos que la misma muestra de germoplasma almacenada en un banco de semillas ha sido utilizada 
para secuenciación genómica, proteómica y RNAseq; estos tres experimentos relacionados pueden asociarse
entre sí apuntando todos al mismo registro en la base de datos BioSamples. De esta manera, es posible 
analizar los patrones de expresión génica y producción de proteínas en esta muestra y compararlos con 
otros para aprender cómo la semilla está adaptada a un ambiente específico. Almacenar los metadatos 
en una sola base de datos, en lugar de que hagan parte de los registros en tres o más base de datos
separadas, es también, más rentable en términos de almacenamiento de datos, un problema que debe 
tomarse extremadamente en serio en la era del big data.

![Relación entre diferentes tipos de datos estándar](https://www.ebi.ac.uk/training/online/courses/bioinformatics-terrified/wp-content/uploads/sites/4/2019/09/fig_4.png)

**Figura 4** Relaciones entre diferentes tipos de estándares de datos. Figura modificada de una diapositiva proporcionada por Sandra Orchard.

## Describir datos y metadatos de manera consistente

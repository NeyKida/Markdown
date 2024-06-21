#¿Qué hace que una base de datos bioinformática sea buena?
Si bien el registro de datos biológicos en sí es útil, la manera en la que es registrada hace una gran diferencia en el valor de la base de datos tanto para los científicos como para los informáticos.
En esta sección discutiremos dos tipos diferentes de base de datos públicas y los mecanismos que utilizan para describir los datos de manera consistente.


# Base de datos primarias y secundarias

## Base de datos primarias 
En la bioinformática, y de hecho en otros campos de investigación intensivos en datos, las bases de datos a menudo se clasifican como primarias o secundarias (Tabla 2). Las **base de datos primarias** se completan con datos derivados experimentalmente  como secuencias de nucleótidos, secuencias de proteínas o estructuras macromoleculares. Los resultados experimentales se suben directamente a la base de datos por los investigadores, y los datos son esencialmente de naturaleza archivística. Una vez que se le haya dado un número de acceso a la base de datos, los datos en las bases de datos primarias nunca son cambiados: estos hacen parte de un registro científico.

## Base de datos secundarias 
Por el contrario, las **base de datos secundarias** contine datos derivados de los resultados del análisis de los datos primarios. A menudo se les conoce como base de datos curada pero este es un nombre poco apropiado porque las bases de datos primarias también son curadas para asegurar que los datos que contienen sean consistentes y precisos.

Las base de datos secundarias suelen recopilar información de diversas fuentes, incluidas otras base de datos (primarias y secundarias), vocabularios controlados (ver sección posterior) y la literatura científica. Estas bases de datos están altamente curadas, frecuentemente utilizan una combinación compleja de algoritmos computacionales y análisis e interpretación manuales para derivar nuevos conocimientos a partir del registro público de la ciencia.

En la última década aproximadamente, las bases de datos secundarias se han convertido en la biblioteca de referencia del biólogo molecular, proporcionando una gran cantidad  (a menudo abrumadora)  de información sobre prácticamente cualquier gen o producto génico que haya sido investigado por la comunidad científica. El potencial para explorar esta información y hacer nuevos descubrimientos es enorme. Nuestro objetivo en este curso es reducir tu energía de activación para que puedas aprovechar al máximo estos recursos en tu investigación.

**Tabla 2** Apectos escenciales de las bases de datos primarias y secundarias. 
|  | Base de datos primaria | Base de datos secundaria |
| --- | ------------------- | ------------------------ |
| **Sinónimos** | 	Base de datos de archivo | Base de datos curada; base de conocimiento |
| **Fuente de datos** | Subido directamente de datos obtenidos experimentalmente por parte de los investigadores | Resultados de análisis, investigación bibliográfica y su interpretación, usualmente de información en bases de datos primarias |
| **Ejemplos** | [ENA](https://www.ebi.ac.uk/ena/browser/home), [GenBank](https://www.ncbi.nlm.nih.gov/genbank/) y [DDBJ](https://www.ddbj.nig.ac.jp/index-e.html) (secuencias de nucleótidos) [ArrayExpress](https://www.ebi.ac.uk/biostudies/arrayexpress) y [GEO](https://www.ncbi.nlm.nih.gov/geo/) (datos de genómica funcional) [Protein Data Bank](https://www.ebi.ac.uk/pdbe/) (PDB; coordenadas de estructuras macromoleculares tridimensionales) | [InterPro](https://www.ebi.ac.uk/interpro/) (familias, motivos y dominios de proteínas) [UniProt Knowledgebase](https://www.uniprot.org/help/uniprotkb) (secuencias e información funcional de las proteínas) [Ensembl](https://www.ensembl.org/index.html) (variación, función, regulación y otros aspectos incorporados en secuencias completas del genoma) |

## Bases de datos híbridas y familias de bases de datos
Muchos recursos de datos tienen características tanto primarias como secundarias. Por ejemplo, [UniProt](https://www.uniprot.org/) acepta secuencias primarias originadas de experimentos de secuenciación de péptidos. No obstante, UniProt también infiere secuencias de péptidos a partir de información genómica, y proporciona una gran cantidad de información adicional, alguna proveniente de anotaciones automáticas (TrEMBL) e incluso de un análisis manual cuidadoso ([SwissProt](https://www.expasy.org/resources/uniprotkb-swiss-prot)).

Algunas bases de datos tienen diferentes 'ramas' para datos primarios y secundarios. Un buen ejemplo de esto es la [colección de datos de ArrayExpress en BioStudies](https://www.ebi.ac.uk/biostudies/arrayexpress): ArrayExpress contiene datos de genómica funcional derivados experimentalmente, mientras que [Expression Atlas](https://www.ebi.ac.uk/gxa/home) utiliza un subconjunto de datos de alta calidad de la colección ArrayExpress para obtener conocimiento sobre patrones de expresión génica en diferentes condiciones.

Para aprender más sobre algunas las bases de datos de EMBL-EBI, prueba el tutorial virtual [A journey through bioinformatics: Explore resources from EMBL-EBI](https://www.ebi.ac.uk/training/online/courses/a-journey-through-bioinformatics/).

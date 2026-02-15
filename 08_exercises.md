# Ejercicios para evaluación

## Aspectos a evaluar:
- ### Comparación de secuencias
- ### Búsqueda de sitios de restricción
- ### Búsqueda de motifs

## Indicaciones

> Deberás envíar tus respuestas en un documento PDF con formato libre indicando tu nombre, **no** se aceptarán documentos en formato .doc o .docx o algún otro tipo.
>
> Para cada sección y las preguntas correspondientes, deberás indicar qué secuencias (o vectores, o sets) elegiste.
>
> En las secciones donde se pregunte acerca de secuencias o motifs ya reportados, incluye el número de acceso de dichos elementos.
>
> No dudes en consultar con tus compañeros, o a mi [correo electrónico](mailtp:vf281@cam.ac.uk) para aclarar cualquier tipo de duda.
>
> La fecha límite de entrega es el viernes 27 de febrero

## Comparación de secuencias

> A continuación se mostrarán 18 secuencias, descarga una (o más) de ellas y realiza los pasos que consideres necesarios para resolver las siguientes preguntas.

1. A que organismo probablemente pertenece la secuencia que elegiste?
2. La secuencia que elegiste, codifica para algúna proteína? Cúal?
3. Cuantas secuencias similares hay en bases de datos?
4. Excluyendo al organismo al cual probablemente pertenezca dicha secuencia, cuantas secuencias hay en bases de datos?
5. La secuencia que elegiste, tiene homólogos en humano? De ser así, indica el o los cromosomas y posiciones de los homólogos
6. Si tu secuencia es codificante, cúal es el homólogo más cercano a nivel de proteína en el linaje de los mamiferos?

### Secuencias

|[Secuencia 1](data/unknown_1.fasta)|[Secuencia 2](data/unknown_2.fasta)|[Secuencia 3](data/unknown_3.fasta)|[Secuencia 4](data/unknown_4.fasta)|[Secuencia 5](data/unknown_5.fasta)|
|-----------------------------------|-----------------------------------|-----------------------------------|-----------------------------------|-----------------------------------|
|[Secuencia 6](data/unknown_6.fasta)|[Secuencia 7](data/unknown_7.fasta)|[Secuencia 8](data/unknown_8.fasta)|[Secuencia 9](data/unknown_9.fasta)|[Secuencia 10](data/unknown_10.fasta)|
|[Secuencia 11](data/unknown_11.fasta)|[Secuencia 12](data/unknown_12.fasta)|[Secuencia 13](data/unknown_13.fasta)|[Secuencia 14](data/unknown_14.fasta)|[Secuencia 15](data/unknown_15.fasta)|
|[Secuencia 16](data/unknown_16.fasta)|[Secuencia 17](data/unknown_17.fasta)|[Secuencia 18](data/unknown_18.fasta)|||

## Restricción enzimática

> En esta sección deberas elegir dos secuencias, una correspondiente a un vector de clonación y una correspondiente a una secuencia desconocida

1. De qué organismo proviene tu secuencia? Qué codifica?
2. Tu vector tiene un sitio de clonación múltiple? Qué enzimas contiene?
3. Qué enzimas de restricción eligirías para clonar tu secuencia en el vector que escogiste?

### Vectores

|[pASK75](data/pASK75.fasta)                  |[pBAD-HisA](data/pBAD-HisA.fasta)  |[pET-3arev](data/pET-3arev.fasta)|
|---------------------------------------------|-----------------------------------|---------------------------------|
|[pETM11-SUMO3GFP](data/pETM11-SUMO3GFP.fasta)|[pGAT](data/pGAT.fasta)            |[pHAT](data/pHAT.fasta)          |
|[pMAL-P2](data/pMAL-P2.fasta)                |[pProEx-HTa](data/pProEx-HTa.fasta)|[pRSET-C](data/pRSET-C.fasta)    |

### Secuencias

|[unknown_19](data/unknown_19.fasta)|[unknown_20](data/unknown_20.fasta)|[unknown_21](data/unknown_21.fasta)|[unknown_22](data/unknown_22.fasta)|
|-----------------------------------|-----------------------------------|-----------------------------------|-----------------------------------|
|[unknown_23](data/unknown_23.fasta)|[unknown_24](data/unknown_24.fasta)|[unknown_25](data/unknown_25.fasta)|[unknown_26](data/unknown_26.fasta)|
|[unknown_27](data/unknown_27.fasta)|[unknown_28](data/unknown_28.fasta)|[unknown_29](data/unknown_29.fasta)|[unknown_30](data/unknown_30.fasta)|
|[unknown_31](data/unknown_31.fasta)|[unknown_32](data/unknown_32.fasta)|[unknown_33](data/unknown_33.fasta)|[unknown_34](data/unknown_34.fasta)|
|[unknown_35](data/unknown_35.fasta)|

## Búsqueda de motifs

> En esta sección deberas elegir uno o más datos de ChIP-Seq
>
> Usando las herramientas [MEME](https://meme-suite.org/meme/tools/meme) , [MAST](https://meme-suite.org/meme/tools/mast) y [TOMTOM](https://meme-suite.org/meme/tools/tomtom) contesta las siguientes preguntas:

1. Cuantos motifs hay en el set que elegiste?
2. Cúal es el e-value del motif mejor representado en tu set? Cúal es la secuencia consenso?
3. De los motifs encontrados en tu set, hay algúno que se parezca a un motif previamente reportado? A cúal?

### Datasets

|[chipseq_1](data/chipseq_1.fasta)|[chipseq_2](data/chipseq_2.fasta)|[chipseq_3](data/chipseq_3.fasta)|
|---------------------------------|---------------------------------|---------------------------------|
|[chipseq_4](data/chipseq_4.fasta)|[chipseq_5](data/chipseq_5.fasta)|[chipseq_6](data/chipseq_6.fasta)|
|[chipseq_7](data/chipseq_7.fasta)|[chipseq_8](data/chipseq_8.fasta)|[chipseq_9](data/chipseq_9.fasta)|
|[chipseq_10](data/chipseq_10.fasta)|                               |                                 |

**[Inicio](README.md)**
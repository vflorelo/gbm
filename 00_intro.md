# Datos biológicos, almacenamiento y distribución

> Una parte importante de la bioinformatica consiste en el almacenamiento y distribucion de los datos biologicos obtenidos experimentalmente.
> 
> Las bases de datos biologicos por lo general resultan de esfuerzos colaborativos entre distintas instituciones, las cuales reciben datos provenientes de diversos grupos de investigacion, realizan procesos de revision y curacion, y finalmente liberan dichos datos al publico con la finalidad de que el conocimiento generado a partir de dichos datos este disponible de forma gratuita.
>
> os datos generados podian ser almacenados en pequenos servidores, e incluso algunas bases de datos eran distribuidas en formato impreso o en unidades opticas (CDs). Actualmente los datos biologicos depositados en bases de datos son sumamente grandes, y esto ha traido la necesidad de centralizar los datos.

# En que formatos puedo obtener datos biológicos

> Las secuencias biologicas albergan informacion por si mismas, sin embargo, en el mundo real, nosotros no podemos hacer mucho sentido de una tira de caracteres. Para ello se han disenado cientos de formatos en los que podemos representar nuestras secuencias

### Raw
> Las secuencias almacenadas en formato raw (crudo, sin formato) unicamente cuentan con la informacion de la secuencia, no es particularmente util si manejamos muchos datos de forma simultanea.
> [ejemplo](data/KP255413.raw)

### Fasta
> El formato fasta consta de un header en la primera linea, en el cual podemos almacenar meta informacion de la secuencia, es decir, informacion de la informacion.
> [ejemplo](data/KP255413.fasta)

### FastQ
> El formato fastq consta de cuatro lineas por secuencia:
> 1. Un header que incluye el identificador de la secuencia
> 2. La secuencia en sí
> 3. Un separador
> 4. Los scores de calidad de cada nucleotido en la secuencia.
> [ejemplo](data/KP255413.fastq)

### Genbank
> El formato GenBank, incluye una tabla de definiciones donde la meta informacion es extensa, por lo cual, los archivos con este formato suelen ser voluminosos.
> [ejemplo](data/KP255413.gbk)

### EMBL
> El formato EMBL es similar al formato GenBank en que incluye una tabla de definiciones, sin embargo, es mas conciso en sus encabezados.
> [ejemplo](data/KP255413.embl)

### GFF/GTF
> El formato GFF es ampliamente utilizado para el almacenamiento de anotaciones de secuencias que van desde 1 nucleótido hasta genomas eucarioticos completos
> [ejemplo](data/KP255413.gff)
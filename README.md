# Analisis-bioinformatico-para-lncRNA-en-celulas-pancreoendocrina
#####Bioinformatic analisys to lncRNA in endocrine cells####
En este repositorio encontrarás una pipeline completa de análisis a secuencias unstranded de ARN de celulas pancreo endocrinas de larvas de pez cebra y usando como referencia un transcriptoma de ensamble de novo de pez cebra adulto (Danio rerio)
Pipeline pertenenciente a mi tesis de pregrado como Bioingeniera
Espero te sea util <3
contacto: eyka_escares@outlook.com
>>>en este repositorio se encuentra la pipeline tal como se extrae de mi trabajo y puedes ajustarlo a tus necesidades.
El orden de los documentos es el siguiente:
>Primer control de calidad de los datos crudos usando FastQC
>Procesamiento de los datos crudos con cutadapt 
>archivo de texto con adaptadores a eliminar en formato fasta 
>Segundo control de calidad post- procesamiento con FastQC 
>Alineamiento de los transcritos pre y post procesamiento
>Estimación de la abundancia de los transcritos (toolkit de Trinity) 
>Normalización de las muestras 
>Evaluación de la reproducibilidad de réplicas biológicas
>Análisis de expresión diferencial con DESeq2
>Filtrado de transcritos con un padj < 0.01
>Extracción de identificadores de lncRNA y no lncRNA 
>Script de la clasificación de los LncRNA con FEELnc
>Ensayo de colocalización
>Ensayo de correlación
>Gráfico circos plot 
>Creación de bases de datos de Danio Rerio 
#saludos ^^

\title{
Evidencia 2
}

\section{Edgar Fabian Lioner Rocha}


\section{Variantes}

20 Paises con mas casos:

01.- MN908947 - SARS-CoV-2 (Original / Baseline) 02.- MN985325 - Estados Unidos 03.- OK356410 India 04.- MW962307 - Brasil 05.- OU791703 - UK 06.- MW332225 - Rusia 07.- MT787745 - Turquia 08.- MW580244 - Francia 09.- MT994881 - Iran 10.- MW633892 - Argentina 11.- MT233523 - España 12.MT470219 - Colombia 13.- MZ362439 - Italia 14.- MZ317675 - Alemania 15.- MW273857 - Polonia 16.MW981442 - Sudafrica 17.- MZ068154 - Filipinas 18.- MZ275298 - Peru 19.- MW947280 - Holanda 20.MW672153 - Chile

Por continentes:

Asia - MN908947 - SARS-CoV-2 (Original / Baseline) America - MN985325 Africa - LR963367 Europa Oceanía - MT007544

Zoonosis - Covid-19 v.s coronavirus animales:

01.- MN908947 - Humano 02.- MT365033 - Tigre 03.- MW626387 - Vison Americano 04.- MZ099821 - Huron 05.- MW562261 - Vison Europeo 06.- MT835139 - Hamster 07.- MZ317675 - Gato 08.- MT628700 - Feliformia 09.- MZ914594 - Lobo 10.- MZ413341 - Leon 11.- AY572034 - Viverridae (SARS) 12.- KY417143 - Murcielago (SARS) 13.- KY417145 - Murcielago 2 (SARS) 14.- AY613950 - Civet (SARS) 15.- AY515512 - Civet 2 (SARS) 16.- HQ890531 - Raton (SARS) 17.- GU553365 - Grivet(Monkey)(SARS) 18.- MT270814 - Perro (SARS) 19.KY417142 - Murcielago 3 (SARS) 20.- KU973692 - Murcielago 4 (SARS)

Covid-19 v.s Coronavirus parecidos:

01.- MN908947 - SARS-CoV-2 Wuhan 02.- MT233519 - SARS-Cov-2 Valencia 03.- MT233526 - SARS-Cov-2 USA-WA1 04.- NC_006577 - HKU1 05.- HM034837 - HKU1 Caen 1 06.- KF530089 - OC43 07.- JQ765563 - NL63 08.- NC_004718 - SARS Tor 2 09.- FJ882931 - SARS P3pp12 10.- FJ882940 - SARS P3pp37 11.AY502929 - SARS TW6 12.- AY502930 - SARS TW7 13.- AY304495 - SARS GZ50 14.- NC_019843 - MERS HCoV-EMC 15.- MT387202 - MERS KNIH_002 16.- KF186567 - MERS Al-Hasa_1 17.- KF186564 - MERS Al-Hasa_4 18.- KF600627 - MERS Al-Hasa 12 19.- KF958702 - MERS-CoV-Jeddah 20.- KF961222 - MERS Qatar 4

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-01.jpg?height=515&width=1892&top_left_y=1985&top_left_x=233)



![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-02.jpg?height=2099&width=1892&top_left_y=320&top_left_x=233)

Diferencia de tamaño entre las variantes de diferentes especies animales

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-05.jpg?height=1054&width=1601&top_left_y=313&top_left_x=251)

#Grafica del tamaño de 20 virus de la familia betacoronavirus en humanos

humanos_variant <- names(humanos_seq_no_alineadas)

humanos_size <- width(humanos_seq_no_alineadas)

df <- data.frame(humanos_variant, humanos_size)

ggplot(df, aes(humanos_variant, humanos_size)) + geom_point(size=3) + ggtitle("Diferencia de tamaño entr 

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-07.jpg?height=2260&width=1531&top_left_y=250&top_left_x=234)



![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-08.jpg?height=2256&width=1528&top_left_y=249&top_left_x=234)



![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-09.jpg?height=2253&width=1528&top_left_y=250&top_left_x=237)



![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-10.jpg?height=2212&width=1586&top_left_y=244&top_left_x=234)



\section{SARS-CoV-2 Top 20 Paises}

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-15.jpg?height=672&width=1114&top_left_y=450&top_left_x=489)

ggtree(virus_plot, branch.length='none', layout='circular') + geom_tiplab()+labs(caption="Coronavirus 

\section{SARS-CoV-2 Continentales}

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-17.jpg?height=672&width=1249&top_left_y=450&top_left_x=492)

Africa

ggtree(continentes_plot, branch.length='none', layout='circular') + geom_tiplab()+labs(caption="Coronal 

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-18.jpg?height=1059&width=981&top_left_y=224&top_left_x=583)

Coronavirus de cada continente

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-18.jpg?height=178&width=982&top_left_y=1389&top_left_x=235)



\section{Zoonosis}

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-19.jpg?height=674&width=1049&top_left_y=449&top_left_x=489)

ggtree(zoonosis_plot, branch.length='none', layout='circular') + geom_tiplab()+labs(title="Coronavirus Coronavirus en animales

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-20.jpg?height=1068&width=1051&top_left_y=325&top_left_x=556)

#Arbol de betacoronavirus parecidos

humanos_plot $<-$ ladderize(humanos_str_filogenetico)

plot (humanos_plot)

title("Coronavirus Humanos") 

\section{Coronavirus Humanos}

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-21.jpg?height=675&width=1049&top_left_y=446&top_left_x=489)

ggtree(humanos_plot, branch.length='none', layout='circular') + geom_tiplab()+labs(caption="Coronavirus 

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-23.jpg?height=2213&width=1243&top_left_y=258&top_left_x=233)



![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-24.jpg?height=2211&width=1445&top_left_y=281&top_left_x=233)



![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-25.jpg?height=1126&width=1441&top_left_y=282&top_left_x=237)

Porcentaje de nucleotidos de variantes de Covid-19 en los paises con mas

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-26.jpg?height=925&width=1596&top_left_y=329&top_left_x=251)

Podemos observar las variantes de los 20 paises con mas casos y a pesar de que el virus muta entre mas contagios hay, la diferencia en el porcentaje de nucleotidos es minima, a duras penas se alcanza a notar Porcentaje de nucleotidos de variantes de coronavirus en animales

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-27.jpg?height=895&width=1591&top_left_y=317&top_left_x=256)

podemos ver como hay una mayor variación, no es tanta pero ya se puede empezar a observar ncia a comparación de las variantes entre paises, al moverse entre paises el virus muta un poco, o necesita mutar todavia mas para poder transmitirse de una especie de animal a otra y por eso empezamos a ver una diferencia mas significativa entre las variantes de diferentes animales Porcentaje de nucleotidos en diferentes virus del genero betacoronavirus

![](https://cdn.mathpix.com/cropped/2022_09_21_4a9b8950efea580b6a44g-28.jpg?height=832&width=1591&top_left_y=313&top_left_x=253)

Podemos observar que en cuando analizamos los diferentes betacoronavirus hay una gran variación en cuestion del porcentaje de nucleotidos de cada virus, como aqui sí son virus liferentes y no solo variantes tiene mas sentido que la diferencia sea mayor, por lo que podemos r que las variantes entre paises tienen menor variación, las variantes entre especies de animales ienen mas variación, pero los virus cuyos genomas son tan diferentes que no se clasifican como

la misma especie son los que muestran la mayor variacion

#Conclusión: Como exploré en el video, los virus más parecidos al Covid-19, es decir los que se podría decir que son su familia cercana son principalmente el SARS y el MERS de acuerdo a PUBMED de NCBI. Este tipo de coronavirus son bastante similares al SARS-CoV-2, los 3 a pesar de tener tasas de mortalidad y contagio diferentes,están presentes en humanos y pertenecen al generi de los betacoronavirus. Se cree que el origen del Covid-19 es del pangolín, sin embargo hay una infinidad de variantes entre especies de mamíferos, hay coronavirus presentes en murciélagos, civets, y numerosos otros animales.

Y podemos observar durante este archivo RMD las similitudes y diferencias entre los virus de la familia betacoronavirus asi como directamente entre variantes del mismo virus de un país a otro y de las variantes entre especies de mamiferos.

Como mencione anteriormente y en el video, los murcielagos son de los principales portadores de los coronavirus. En cuestión de la composición de todos estos virus, los que son distintos pero del mismo genero, es decir el SARS, SARS-CoV-2y el MERS presentan una variación significante en su composición de nucleotidos, mientras que las variantes del mismo SARS-CoV-2 entre especies de mamiferos presentan una variación de composición de nucleotidos reducida y finalmente las variantes del mismo virus pero entre países diferentes son practicamente iguales, si hay variación pero esta es minima en comparación de los otros dos casos de estudio
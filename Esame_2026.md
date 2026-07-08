> #### Cristina Ferro
>> ##### matricola n. 1237306
 # Areosol ad alta quota
 ## Analisi del particolato antropogenico sull'arco alpino occidentale
 (immagine satellitare dell'arco alpino oggetto di studio)
 
 ## Obiettivi del progetto
 Il progetto esamina la presenza di areosol nell'area alpina di ... (del progetto), focalizzando l'attenzione ad un altitudine superiore ai 1000m.

# Metodologia
## Raccolta delle immagini
... file Copernicus e Cams 
I dati sono stati ottenuti dalla piattaforma di Copernicus, grazie al satellite Sentinel5. Sempre Copernicus ha fornito il DEM delle aree di studio da cui è stato possibile ottenere l'altimetria. (link al sito)

## Impostazione della working directory
(setw)...

 ``` r
...
```

 ## Importazione dei pacchetti

 I pacchetti inseriti su R per questo progetto sono stati i seguenti:

 ``` r
library(terra)
library(imageRy)
library(ggplot2) #per manipolare i dati e fare grafici
install.packages("sf") #per gestire gli shapefile
library(sf)
```

## Importazione dei dati






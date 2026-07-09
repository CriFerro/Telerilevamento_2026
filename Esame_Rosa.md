# Guardare il cambiamento climatico

## sottotitolo su ghiaccio e vegetazione

Data were gathered from the [Earth Observatory site](https://earthobservatory.nasa.gov/).

Packages used:

``` r
library(terra)
library(imageRy)
library(viridis) # in order to plot images with different viridis color ramp palettes
```
## Obiettivi del progetto R
- **DVI** (Difference Vegetation Index)  
- **NDVI** (Normalized Difference Vegetation Index)
---

# Metodologia
## Impostazione della working directory

``` r
setwd("C:\\Esame_telerilevamento")
```
## Importazione dell'immagine

``` r
Mont_blanc00 <- rast("Monte_Bianco_Bande_2000.tif")
Mont_blanc25 <- rast("Monte_Bianco_Bande_2025.tif")
```

## Visualizzazione con colori reali


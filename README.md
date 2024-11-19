# R-notebooks

## table.Rmd
table.Rmd was used to make the table for annoucement publication , Howler project

## mpa-level filtering.Rmd
This is to filter out different taxonomic levels from metaphlan4 output. this has genus and species level

## Maaslin2
to download Maaslin2 ( in 2024) I faced some problems.

"if(!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("Maaslin2")" 

did not work for my system although the R and BiocManager versions were up-to-date. It kept saying Masslin2 is not aailable for my version of R.
Although after installing latest devtools and Rtools this worked:

if(!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("Maaslin2")


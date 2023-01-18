FROM risserlin/bcb420-base-image:winter2023

# Install DESeq2 from Bioconductor
RUN R -e "BiocManager::install('DESeq2')"

# Install pheatmap from CRAN
RUN install2.r \
    -d TRUE \
    -r 'https://cran.rstudio.com' \
    pheatmap
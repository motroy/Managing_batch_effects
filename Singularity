Bootstrap: docker
From: r-base:3.5.3

%post
apt update && apt install -y git curl wget less locate build-essential openssh-server apt-transport-https software-properties-common libssl-dev libcurl4-openssl-dev libmagick++-dev libgmp-dev

wget https://cran.r-project.org/src/contrib/Archive/glmnet/glmnet_2.0-18.tar.gz
wget https://cran.r-project.org/src/contrib/Archive/latticeExtra/latticeExtra_0.6-28.tar.gz
R Rscript -e 'install.packages("knitr")'
R Rscript -e 'install.packages("xtable")'
R Rscript -e 'install.packages("ggplot2")'
R Rscript -e 'install.packages("vegan")'
R Rscript -e 'install.packages("cluster")'
R Rscript -e 'install.packages("gridExtra")'
R Rscript -e 'install.packages("pheatmap")'
R Rscript -e 'install.packages("ruv")'
R Rscript -e 'install.packages("lmerTest")'
R Rscript -e 'install.packages("glmnet_2.0-18.tar.gz",type="source")'
R Rscript -e 'install.packages("foreach")'
R Rscript -e 'install.packages("glmnet_2.0-18.tar.gz",type="source")'
R Rscript -e 'install.packages("latticeExtra_0.6-28.tar.gz",type="source")'
R Rscript -e 'install.packages("BiocManager")'
R Rscript -e 'BiocManager::install("sva")'
R Rscript -e 'BiocManager::install("limma")'
R Rscript -e 'BiocManager::install("variancePartition")'
R Rscript -e 'BiocManager::install("pvca")'
R Rscript -e 'BiocManager::install("mixOmics")'
R Rscript -e 'BiocManager::install("AgiMicroRna")'
R Rscript -e 'BiocManager::install("bapred")'
R Rscript -e 'BiocManager::install("phyloseq")'

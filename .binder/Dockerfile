FROM rocker/geospatial:latest

USER root
# Copy your repository contents to the image

RUN install2.r --error \
    --deps TRUE \
    learnr \
    shiny \
    here \
    cowplot \
    fivethirtyeight \
    plotly \
    skimr \
    visdat \
    NHANES \
    rlang 

COPY . ${HOME}
COPY ./inst/tutorials/dataLiteracy ${HOME}/dataLiteracy

RUN chown -R ${NB_USER} ${HOME}

USER ${NB_USER}

FROM rocker/geospatial:latest

RUN install2.r --error \
    --deps TRUE \
    rlang \
    shiny \
    learnr

RUN install2.r --error \
    --deps TRUE \
    here \
    cowplot \
    fivethirtyeight \
    plotly \
    skimr \
    visdat \
    NHANES 
    
USER root   
COPY . ${HOME}
COPY ./inst/tutorials/dataLiteracy ${HOME}/dataLiteracy

RUN chown -R ${NB_USER} ${HOME}

USER ${NB_USER}

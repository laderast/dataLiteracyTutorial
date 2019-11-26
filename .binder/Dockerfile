FROM rocker/binder:latest

ARG NB_USER
ARG NB_UID

#RUN install2.r --error \
#    --deps TRUE \
#    rlang \
#    shiny \
#    learnr \
#    here \
#    cowplot \
#    fivethirtyeight \
#    plotly \
#    skimr \
#    visdat \
#    NHANES 
    
USER root   
COPY . ${HOME}
COPY inst/tutorials/dataLiteracy/ ${HOME}/dataLiteracy/

RUN chown -R ${NB_USER} ${HOME}

USER ${NB_USER}

RUN if [ -f install.R ]; then R --quiet -f install.R; fi

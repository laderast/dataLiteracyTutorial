FROM rocker/binder:3.5.0

# Copy your repository contents to the image
COPY --chown=rstudio:rstudio . ${HOME}

ADD .binder/install.R /tmp/
RUN R -f /tmp/install.R

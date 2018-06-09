FROM stevenpollack/docker-rserve

MAINTAINER "Henrique Costa" henrique.costa@gmail.com

RUN install2.r --error \
    -r "https://cran.rstudio.com" \
    caret && \
    rm -rf /tmp/downloaded_packages/ /tmp/*.rds

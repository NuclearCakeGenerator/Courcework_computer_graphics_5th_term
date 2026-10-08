FROM ubuntu:24.04

ENV DEBIAN_FRONTEND=noninteractive \
    LANG=C.UTF-8 \
    LC_ALL=C.UTF-8

RUN apt-get update \
    && apt-get install --no-install-recommends --yes \
        fonts-dejavu \
        fonts-liberation \
        fonts-texgyre \
        ghostscript \
        latexmk \
        poppler-utils \
        python3 \
        texlive-extra-utils \
        texlive-fonts-recommended \
        texlive-lang-cyrillic \
        texlive-latex-extra \
        texlive-xetex \
        git \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspaces/Courcework_computer_graphics_5th_term/
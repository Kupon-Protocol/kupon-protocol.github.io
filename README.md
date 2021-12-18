# Kupon Protocol Blog

## Install

    pip install -r requirements.txt

## Run

    pelican content
    cd output && python -m pelican.server

## Build an output

    pelican -s pelicanconf.py

## Push to GH Pages

    ghp-import output
    git push git@github.com:kupon-protocol/kupon-protocol.github.io.git gh-pages:master

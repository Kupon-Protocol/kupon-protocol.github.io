# Kupon Protocol Blog

## Install

    pip install -r requirements.txt

## Build an output

    pelican -s pelicanconf.py

## Push to GH Pages

    ghp-import output
    git push git@github.com:kupon-protocol/kupon-protocol.github.io.git gh-pages:master

doctype html
html
    head
        meta(charset='utf-8')
        meta(http-equiv='X-UA-Compatible', content='IE=edge,chrome=1')
        meta(name='description', content='')
        meta(name='viewport', content='width=device-width, initial-scale=1')

        title= title
        link(rel='stylesheet', href='/stylesheets/style.css')
        link(rel='stylesheet', href='/stylesheets/main.css')
        link(rel="icon", href="favicon.svg")

    body
        block content

# Shipping app

## Development

Install fig - http://www.fig.sh/install.html

    fig up -d                   # build the iojs and nginx images and run nginx
    fig run app npm install     # install npm dependencies
    fig run app npm run watch   # watch js files and create bundle.js for development

## Production

    fig run app npm run build   # create bundle.js for production

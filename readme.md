# Shipping app

## Development

Install fig - http://www.fig.sh/install.html

    fig up                      # build the image
    fig run app npm install     # install npm dependencies
    fig run app npm run watch   # watch js files and create bundle.js for development


## Production

    fig run app npm run build   # create bundle.js for production

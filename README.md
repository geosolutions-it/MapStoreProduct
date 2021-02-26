# MapStore Product

WIP: migration to new project structure

## Development Quick Start

Clone the repository with the --recursive option to automatically clone submodules:

`git clone --recursive https://github.com/geosolutions-it/mapstore-product.git`

Install NodeJS from [here](https://nodejs.org/en/download/releases/).

Start the development application locally:

`npm install`

`npm start`

The application runs at `http://localhost:8081` afterwards.

## Compile the client bundle

- set the max_old_space_size env variable if the compile script throws this error ERR_WORKER_OUT_OF_MEMORY

`export NODE_OPTIONS=--max_old_space_size=3072`

- run the command to compile the frontend

`npm run compile`

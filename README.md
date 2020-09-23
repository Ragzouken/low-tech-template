# exquisite tool b

tools for developing the tool "exquisite tool b"

## how to get started

### install developer dependencies
install [nodejs](https://nodejs.org/en/) (this gives you `npm` which is used to
install the next stuff) 

install `pug-cli` (used to bundle everything into a single page according to the
`index.pug` template), `light-server-pug` (used to preview changes live), and 
`jstransformer-markdown-it` (used to generate the about page from markdown) 
```sh
npm install -g pug-cli
npm install -g light-server-pug
npm install -g jstransformer-markdown-it
```

### developer scripts
run a local server that loads the standalone page and refreshes it 
whenever you make changes:
```
./watch.cmd
```

build the standalone page to `dist/exquisite-tool-b.html`:
```
./build.cmd
```

## license
[ACSL License](./LICENSE)

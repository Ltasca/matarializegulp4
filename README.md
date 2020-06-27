# Materializegulp4
Esrutura de projeto utilizando matarializeCSS e fontawesome 
Compila, concatena e minifica css e js utilizando gulp 4 
Roda servidor browsersync para exibir as alterações em tempo real tanto na estação de trabalho como em outros dispositivos da rede de forma sincronizada.

#### Setup

git clone https://github.com/Ltasca/materializegulp4.git
cd materializegulp4
npm install
npm run build

## How to Use

#### `npm run build`
This will create minified materialize css & js files. Then it will automatically run a server that renders everything in the `dist/` folder and watch for any changes made in the `src/sass/`, `src/js/`, and in `dist/`. Any change will automatically prompt the browser to reload.

#### `npm run watch`
The same as `npm run build` without the initial part of constructing the minified files. It just launches the browser and watches.

#### `npm run css`
1. Compiles the sass files into a compressed css file.
2. Autoprefixes all rules for Chrome 30+, Firefox 30+, IE 10+, and Safari 8+.
3. Renames the final file into "materialize.min.css".

#### `npm run js`
Transpiles all of the js files with babel, concats them into one file, and then minifies it.

# VirtualMenu-Giacosa

Comandos de ayuda para la configuracion de SASS

/* Para inicializar NPM*/
npm init  
npm init -y (Crea todo con valores por defecto)

/* Instalo node sass */
npm install -D node-sass nodemon

/* Configuro Package.json e inserto dos lineas dentro de scripts */
"build-css": "node-sass --include-path scss scss/prueba.scss css/pruebacss.css",
"watch-css": "nodemons -e scss -x \"npm run build-css\""

/* Por ultimo para correr el sass*/
npm run watch-css
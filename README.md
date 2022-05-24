# VirtualMenu-Giacosa


/* Para inicializar NPM custom*/
npm init 
/* Crea todo por defecto */
npm init -y 


/* Comandos de ayuda para la configuracion de SASS*/
/* Instalo node sass */
npm install -D node-sass nodemon



/* Configuro Package.json e inserto dos lineas dentro de scripts */
"build-css": "node-sass --include-path scss scss/prueba.scss css/pruebacss.css",
"watch-css": "nodemons -e scss -x \"npm run build-css\""


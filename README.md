# VirtualMenu-Giacosa


A simple Web Page with HTML, CSS, SASS full responsive with effects. <br />

How to config SASS<br />
/* Start Project*/
npm init   <br />
npm init -y (Crea todo con valore s por defecto) <br />

/* Install SASS */
npm install -D node-sass nodemon <br />


/* Configuro Package.json e inserto dos lineas dentro de scripts */ <br />
"build-css": "node-sass --include-path scss scss/prueba.scss css/pruebacss.css", <br />
"watch-css": "nodemons -e scss -x \"npm run build-css\"" <br />
<br />

/* To run*/ <br />
npm run watch-css <br />

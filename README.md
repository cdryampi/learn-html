# learn-html

Repositorio para aprender HTML

- Teoría con ejemplos: https://www.w3schools.com/html/default.asp
- Documentación "oficial": https://developer.mozilla.org/es/
- Verificar si se puede usar una etiqueta: https://caniuse.com/

Hoja de estilos de Water.css:

- https://watercss.kognise.dev/

## Ejercicios

1. https://www.auladiv.com/ejercicios/html-basico/

## Instalación de tailwindcss

1. Instalar Node.js: https://nodejs.org/es/
2. Instalar tailwindcss: https://tailwindcss.com/docs/installation
3. instalar el paquete de tailwind `npm install -D tailwindcss`
4. Crear el archivo de configuración de tailwind `npx tailwindcss init`
5. Modificar el archivo de configuración `tailwind.config.js`

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./*.{html,js}", "./ejercicios/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

6. Initializar tailwindcss `npx tailwindcss -i ./src/css/styles.css -o ./src/css/output.css --watch`

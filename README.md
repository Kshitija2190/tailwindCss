tailwind cli installation

npx tailwindcss init

tailwind.config.js

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

src/input.css

@tailwind base;
@tailwind components;
@tailwind utilities;

npx tailwindcss -i ./src/input.css -o ./dist/style.css --watch

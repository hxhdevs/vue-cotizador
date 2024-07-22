# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about IDE Support for Vue in the [Vue Docs Scaling up Guide](https://vuejs.org/guide/scaling-up/tooling.html#ide-support).


# Como instalar VUE?
npm create vite@latest
- despues de esto mostrara en terminal el nombre que se le dara al proyecto, opciones y debes escoger las tecnologias en este caso VUE
Vue
JS
- tipear en terminal dentro del proyecto creado apra mostrar el proyecto en el navegador
npm install
npm run dev

# Single File componente
- Que es?
- basicamente es tener script, template y style en un solo archivo en este caso en App.vue
# instalando tailwindcss en vue
- en este caso la instalamos como desarrollo
npm install -D tailwindcss postcss autoprefixer
- se agrega en automatico en package.json y despues tipeamos
npx tailwindcss init -p
- eso creara los siguientes archivos
tailwind.config.js
postcss.config.js
# Componentes
- Los componentes son partes reutilizables, utilizan la extension .vue y se pueden pasar informacion con props
# API Styles
los componentes de Vue se escriben de dos maneras 
- Cuando utilizarlos?
Option API(es para personas que van iniciando y personas con orientacion POO) 
Composition API(solo si todo el proyecto sera con VueJS)
# eventos en Vue JS
# states en Vue JS
- en vue se usa states con ref o reactive y se importa del siguiente modo
import {ref,reactive} from 'vue'

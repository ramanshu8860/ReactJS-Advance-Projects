After Downloading the Project from my Git or after cloning the project using any IDE to open it like Visual Studio:
Then Run Following Commands
1) Open the Project with Visual Studio or any IDE.
2) Then run the following Command:
    //   FOR NPM: 
    i) npm install
   ii) npm install react-router-dom
   iii) if you are using Vite for Creating React JS project:
         then run :
           npm install @vitejs/plugin-react

   Then, update your vite.config.js:
    import { defineConfig } from 'vite';
     import react from '@vitejs/plugin-react';

   export default defineConfig({
        plugins: [react()],
   });

   if the plugin is already added then leave it:



In short run these Commands:
    i) npm install
    ii) npm install react-router-dom
    iii) npm install @vitejs/plugin-react
   

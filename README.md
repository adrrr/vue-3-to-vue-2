### from vue 3 to vue 2

- run these commands
```
npm i vue@2
npm r @vitejs/plugin-vue
npm i -D @vitejs/plugin-vue2
```
- update main.ts to put back classic vue 2 content
- update vite config to use @vitejs/plugin-vue2 instead of @vitejs/plugin-vue
- update vue templates to use only one root element
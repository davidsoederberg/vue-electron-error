vue ui -> create project -> manual -> add unit test, remove lint (save time) -> mocha + chai -> add plugin -> install vue-cli-plugin-electron-builder 
-> finish install 

1. npm run test:unit -> no error
2. Add `import { ipcRenderer } from 'electron'` in HelloWorld.vue
3. npm run test:unit -> error

# VueJS

## Directives
### v-on 
```vue
  <button v-on:click="age++">Increase Age</button>
  <button @click="age--">Decrease Age</button>
  <button @click="changeTitle('The Amazing Vue Course')">Change Title</button>
```



### v-if & v-else 
```vue
  <div v-if="showBook">
      <p>{{ title }} - {{ author }} - {{ age }}</p>
  </div>
  <div v-else>
      <p>No book available</p>
  </div>
```

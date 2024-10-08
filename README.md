# VueJS

## Directives
### v-on 
```vue
  <button v-on:click="age++">Increase Age</button>
  <button @click="age--">Decrease Age</button>
  <button @click="changeTitle('The Amazing Vue Course')">Change Title</button>
```


### Events
```vue
      <div class="box" @mouseover="handleEvent($event, 'mouseover')">Mouse over me</div>
      <div class="box" @mouseleave="handleEvent">Mouse leave me</div>
      <div class="box" @click="handleEvent">Click me</div>
      <div class="box" @dblclick="handleEvent">Double click me</div>
      <div class="box" @mousemove="handleMouseMove">Mouse position: {{ x }}, {{ y }}</div>
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


### v-show
```vue
  <div v-show="showBook"> Book Visibility: {{ showBook }}</div>
```


### v-for
```vue
  <div v-for="book in books">
      <p>{{ book.title }} - {{ book.author }} - {{ book.age }}</p>
  </div>
```


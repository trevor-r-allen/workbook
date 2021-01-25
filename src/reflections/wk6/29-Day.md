# Day 29
__01/21/2020__

## Thoughts on Nested Routes in Vue.js

### What is a nested route?
An additional route with its own path and components. It is created under the `children` property of a higher level route.

### When might you use a nested route?
A nested route could be used to allow navigation to deeper endpoints within the same page of the parent route. For example having multiple tabs that switch the information displayed below them based on the paths of the nested routes.

### Can you pass parameters through nested routes? When might you use them?
You can pass parameters to nested routes, using a colon.  This could be used whenever the desired endpoint is dynamic, such as when its desired navigation is to a specific blog or user profile targeted by an id.

#### Afternoon Lab: [Pokedex Vue](https://trevor-r-allen.github.io/pokedex-vue/)
####                [Pokedex Vue Code](https://github.com/trevor-r-allen/pokedex-vue)
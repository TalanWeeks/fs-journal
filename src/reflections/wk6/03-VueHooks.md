# Understanding Vue.js Lifecycle Hooks

## What are lifecycle hooks?

* Lifecycle hooks are a window into how the library you're using works behind-the-scenes. 

## What are lifecycle hooks used for?

* Lifecycle hooks allow you to know when your component is created, added to the DOM, updated, or destroyed.

## What are mounting hooks? When might you use them?

* They allow you to access your component immediately before and after the first render. They do not, however, run during server-side rendering. Use mounting hooks if you need to access or modify the DOM of your component immediately before or after the initial render.

link--https://talanweeks.github.io/gregslist-vue/
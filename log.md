# 100 Days Of Code - Log

### Day 0: Monday 2 November 2020
#### Learning Vue.js

**Today's Progress**: Set up a Vue project, learn about Vue components, events and vue router.

**Thoughts:** 

- Vue was initially not installing as I didn't have permission to do so on my system. However, a quick google and look at a Stack Overflow thread suggested using `sudo npm i @vue/cli -g` rather than just `npm i @vue/cli -g` as I was originally doing.
- It was interesting to learn that you can set up a Vue project using Vue UI (in terminal: `vue ui`), as well as just the command line (`vue create *project name*`). This brings up a Vue user interface in the browser - from there you can add vue router, start the server, and view dependencies.
- I have build projects in React before, so it was useful to see the similarities between React and Vue.
- Vue also seems similar to Handlebars in the use of views and layouts.

**Link to work:** [Vue todo list app](https://github.com/shrena-patel/vue-todo)

---


### Day 0: Tuesday 3 November 2020
#### Vue.js Skillshare course

**Today's Progress**: Learning more about Vue.js..

**Thoughts:** 

***Directives***

- Directives are Vue-specific syntax and go where HTML attributes (such as `href` or `src`) go. They always start with a '`v-`' prefic and the value of a directive is evaluated as JavaScript.
- Directive can take arguments by adding a colon after the directive name, such as `<a v-bind:href="url">`, which dynamically binds data to a regular HTML attribute.
- Using the `v-for` directive, you can loop through an array in a similar way to how you would in a for loop or map function.
- `v-model` directive is used for two-way data binding on any user input HTML element - text input, radio buttons etc. When data in such an element that has a v-model changes, it updates the data property it is tied to.

***Methods***

- Methods are held in an object as a property of the vue instance, exactly as the `data` object is.
- Instead of holdings strings or arrays like the data object does, the methods object holds functions.
- You can then use the `v-on` directive with methods, which allows you to set event listeners on HTML elements.
- Most commonly used as `<button v-on:click="name-of-function-declared-in-methods-object">`.

***Computed properties***

- Properties held in a "computed" object are different from a data object.
- Similar to methods, properties inside the computed object have values of a function.
- Whenever the values within the computed object are updated, Vue updates all instances of that value. 

**Link to work:** [Simple vue practice](https://codepen.io/shrepat/pen/OJXELNX?editors=1111)



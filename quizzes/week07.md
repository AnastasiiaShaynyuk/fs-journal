# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
One-way binding - changes to the data property will update the template, but changes in the template will not update the data property(v-bind or :).
Two-way binding - changes in the data property will update the template, and changes in the template will update the data property(v-model).
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single-page application.
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
- quick loading time
- seamless user experience
- no extra queriers to server
- caching capabilities

```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
The onMounted method is a lifecycle hook that is called when a component is mounted in the DOM.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
The v-model attribute in Vue is a two-way data binding directive that provides a convenient way to bind data between form elements and component state. You can use it on a form element.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
It is used to attach event listeners to elements in the component's template. With v-on, you can listen for a variety of DOM events such as click, input, submit ets.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if, v-else, v-for, v-show
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
It goes with v-for and is used to provide the unique identifier for each item in the list.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
The <slot></slot> element allows you to define a placeholder for content that will be provided by the parent component when the component is used. It can be useful for modals. 
```
# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
main.js
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
A component can be used multiple times throughout your application and can have its own data, methods, and lifecycle hooks.
A page is typically a higher-level component that represents a specific view or screen of your application. Pages are often composed of one or more components and are responsible for rendering the overall structure of the page and passing data down to child components.
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
<template></template>, 
<script></script>,
<style></style>
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The L in SOLID stands for the Liskov Substitution Principle. It helps ensure that your components are modular, reusable, and can be easily swapped out with other components without causing any unexpected issues.
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
<router-link></router-link>
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
The AppState refers to the global state of your application, which is shared across all components. 
The state object within a component refers to the local state of that component, which is only accessible and modifiable within that component.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
Services are typically used to abstract away complex business logic into reusable and modular functions that can be easily used across multiple components.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
App.vue
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
The <style></style> tag is used to alter the styling of your entire Vue project.  Adding the scoped attribute to this tag will limit it to just the component it exists.  Fill in the blank.
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
.reactive()
```
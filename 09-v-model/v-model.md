# V-Model Directive
Compared to normal JavaScript, it is easier to work with forms in Vue because the v-model directive connects with all types of input elements in the same way.

v-model creates a `link between the input element value attribute and a data value in the Vue instance`. When you change the input, the data updates and when the data changes, the input updates as well `(two-way binding)`.

## Two-way Binding

As we have already seen in the shopping list example on the previous page, v-model provides us with a two-way binding, meaning that the form input elements update the Vue data instance, and a change in the Vue instance data updates the inputs.

Note: The v-model two-way binding functionality could actually be achieved with a combination of v-bind:value and v-on:input:

v-bind:value to update the input element from the Vue instance data,
and v-on:input to update the Vue instance data from the input.
But v-model is much easier to use so that is what we will do.
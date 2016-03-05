# Vue Atom Snippets
A collection of Atom snippets for Vue.js

###Directives
All directives in the [Vue.js API](http://vuejs.org/api/#Directives) are included.

For most cases the trigger is the name of the directive without the `v-`:
* `text` + <kbd>Tab</kbd> = `v-text=""`
* `show` + <kbd>Tab</kbd> = `v-show=""`
* `else` + <kbd>Tab</kbd> = `v-else`
* You get the idea

For events I've omitted `v-on` and only included the shorthand `@`. You get a tab stop so you can write the type of event and other modifiers like `prevent` or `enter` also included as snippets. Note that because of a limitation of Atom snippets once you trigger a nested snippet you exit execution of the first snippet (you will not get tab stops afterwards).
* `click` + <kbd>Tab</kbd> = `@click=""`
* `submit` + <kbd>Tab</kbd> = `@submit=""`
* `keyup` + <kbd>Tab</kbd> = `@keyup=""`

For properties I've omitted `v-bind` and only included the shorthand `:`. Similar to the events you get a tab stop to include additional options like `sync` also included as snippets.
* `class` + <kbd>Tab</kbd> = `:class=""`
* `prop` + <kbd>Tab</kbd> = `:prop=""`

### Filters
All filters in the [Vue.js API](http://vuejs.org/api/#Filters) are included as snippets.

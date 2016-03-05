# Vue Atom Snippets
A collection of Atom snippets for Vue.js

###Directives
All directives in the [Vue.js API](http://vuejs.org/api/#Directives) are included.

For most cases the trigger is the name of the directive without the `v-`:
* `text` + <kbd>Tab</kbd> = `v-text=""`
* `show` + <kbd>Tab</kbd> = `v-show=""`
* `else` + <kbd>Tab</kbd> = `v-else`
* You get the idea

For events I've omitted `v-on` and only included the shorthand `@`. You get a tab stop so you can write the type of event and other modifiers like `prevent` or `enter` also included as snippets.
* `click` + <kbd>Tab</kbd> = `@click=""`
* `submit` + <kbd>Tab</kbd> = `@submit=""`
* `keyup` + <kbd>Tab</kbd> = `@keyup=""`

For properties I've omitted `v-bind` and only included the shorthand `:`. Similar to the events you get a tab stop to include additional options like `sync` also included as snippets.
* `class` + <kbd>Tab</kbd> = `:class=""`
* `prop` + <kbd>Tab</kbd> = `:prop=""`

### Filters
All filters in the [Vue.js API](http://vuejs.org/api/#Filters) are included as snippets.

### Vue Router
In progress. So far only `v-link` is there with its different options, and `<router-view></router-view>`. Take note that there is a bug in autocomplete for snippets and the options (params, active class, etc) will not show in the autocomplete list, but I assure these work.
* `link` + <kbd>Tab</kbd> = `v-link{path:}`
* `params` + <kbd>Tab</kbd> = `params: {}`
* `activeclass` + <kbd>Tab</kbd> = `activeClass: ''`
* You get the idea.

### Note about nested snippets
 There is a bug in the snippets Atom package with nested snippets. Once you trigger a nested snippet you exit execution of the first snippet (you will not get tab stops afterwards). [This bug has been solved, but the pull request has not been accepted yet.](https://github.com/atom/snippets/pull/192#issuecomment-192744795)


Changelog
===============================================================================


## v1.4.2

- Fix `java.lang.IllegalStateException: it.virtualFile must not be null` (#37)


## v1.4.1

- Revert automated build process to use JDK 1.7 again


## v1.4.0

- Add IntelliJ 14 (all `141.*` builds) compatibility
- Add IntelliJ 16 (all `144.*` builds and above) compatibility
- Only enable JSHint automatically if `.jshintrc` file was found
- Add basic support for Ember.js addons
- Use locally installed `ember` executable


## v1.3.1

- Fix Ember.js project detection in PyCharm, WebStorm, RubyMine, ...
- Fix Ember.js project detection if subfolders contain Java files
- Fix ember-cli exception and broken timeout
- Add icons for Darcula UI theme


## v1.3.0

- `Navigate → Related Symbol...` for tests
- Show file type icons in project tree view
- more Live Templates for HTMLBars
- Basic reference resolving and completion for e.g. `DS.belongsTo('user')`

![Reference Resolving](doc/references.png)

![Completion](doc/completion.png)

- Generate Ember.js files via `ember generate`

![Blueprints Dialog](doc/blueprints-dialog.png)



## v1.2.0

- Enable JSHint using `.jshintrc`
- Marks `node_modules` and `bower_components` as library folders
- Quick navigation via `Navigate → Related Symbol...` for all major app components
- Live templates

![Live Templates](doc/live-templates.png)


## v1.1.1

- Fix missing icon file


## v1.1.0

- Quick navigation via `Navigate → Class...` for all major app components

![Navigate → Class...](doc/goto-class.png)


## v1.0.2

- Adjust plugin description


## v1.0.1

- Adjust plugin vendor information


## v1.0.0

- Ember.js project discovery (via `app/app.js`) when imported from existing sources
- Automatically sets the language level to ES6
- Marks `app`, `public` and `tests` folders as special folders

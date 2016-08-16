Brightspot Base Snippets for Atom Editor
========================================

Installation
------------

Install Handlebars support:

`apm install atom-handlebars`

Then clone this repo. From a command line inside the project directory, run:

`apm link .`

Then restart Atom.

Usage
-----

Atom snippets documentation is [here](http://flight-manual.atom.io/using-atom/sections/snippets).

In a .js, .json, or .hbs file, type `bsp` to see a list of available snippets. They use Atom's tab completion feature

Example
-------

In a .hbs file, type `bsp` and you'll see a menu that looks like this showing you available Brightspot Base Handlebars snippets.

![BSP Menu](https://cloud.githubusercontent.com/assets/1325345/17699078/a7b14fde-638c-11e6-8c48-a03eacaf6e33.png)

After hitting enter on the `BSP Define Block` option, the snippet will be inserted in the page with `exampleModule` highlighted. Type the name of your module to replace `exampleModule`.

![BSP Module Snippet First Tab](https://cloud.githubusercontent.com/assets/1325345/17699183/5b89aca4-638d-11e6-8022-eaa42e87b92b.png)

Type the Tab key, and the module extend path will be highlighted (there is also a standalone module snippet without the extend attribute). Type the path of the module you are extending.

![BSP Module Snippet Second Tab](https://cloud.githubusercontent.com/assets/1325345/17699103/df4f2c22-638c-11e6-9551-8ed49e65ced7.png)

Type Tab again, and `exampleElement` will be highlighted in two places. Type the name of your first element once and both strings will be replaced.

![BSP Module Snippet Third Tab](https://cloud.githubusercontent.com/assets/1325345/17699108/e8b5f44e-638c-11e6-9370-1246f5f69ddb.png)

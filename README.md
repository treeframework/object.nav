# Nav

The `nav` object is simple creates navigation items out of a `ul` or `ol`.

## Dependencies

The `nav` object depends on two other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [tools.functions](https://github.com/treeframework/tools.functions)

If you install the `nav` object using Bower, you will get these dependencies at
the same time. If not using Bower, please be sure to install and `@import` these
dependencies in the relevant way.

## Installation

You can install `nav` object via Bower, npm, Git Submodule, or copy and paste.

### Install using bower:

```sh
$ bower install tree-nav --save
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "bower_components/tree-nav/object.nav";
```

### Install using npm:

```sh
$ npm install tree-nav --save
```

### Install as a Git Submodule:

```sh
$ git submodule add git@github.com:treeframework/object.nav.git
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "object.nav/object.nav";
```

### Install via file download

The least recommended option for installation is to simply download
`_object.nav.scss` into your project and `@import` it into your project in its 
Object layer.

## Usage

Basic usage of the Nav object uses the required classes:

```html
<ul class="o-nav">
    <li class="o-nav__item">
        <a class="o-nav__link" href="#">Foo</a>
    </li>
    <li class="o-nav__item">
        <a class="o-nav__link" href="#">Bar</a>
    </li>
</ul>
```

## Options

Other, optional classes can supplement the required base classes:

* `.o-nav--[tiny|small|large|huge]`: alter the padding between nav links.
* `.o-nav--clean`: removes whitespace caused by `inline-block`.
* `.o-nav--stacked`: vertical mode.
* `.o-nav--fit`: occupy 100% of the available width of its parent.

For example:

```html
<ul class="o-nav  o-nav--stacked">
    <li class="o-nav__item">
        <a class="o-nav__link" href="#">Foo</a>
    </li>
    <li class="o-nav__item">
        <a class="o-nav__link" href="#">Bar</a>
    </li>
</ul>
```

## Credits

* **[inuitcss](https://twitter.com/inuitcss)** Powerful, scalable, Sass-based, BEM, OOCSS framework.

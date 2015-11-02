# tex-element

Render TeX live on the web using KaTeX.

## Usage

Install via Bower:

```sh
npm install --save tex-element
```

Import it directly:

```html
<link rel="import" href="bower_components/tex-element/tex-element.html">
```

This may change if you are using a tools like Gulp, Grunt or Webpack.

#### Use it

```html
<tex-element display formula="
  \int u \frac{dv}{dx}\,dx=uv-\int \frac{du}{dx}v\,dx
"></tex-element>
```

#### Inline use

```html
This <tex-element formula="\int_{a}^{b} x^2 dx"></tex-element> is a inline formula.
```

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

```sh
npm install -g bower
```

Then, go ahead and download the element's dependencies:

```sh
bower install
```

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

```sh
npm install -g polyserve
```

And you can run it via:

```sh
polyserve
```

Once running, you can preview your element at
`http://localhost:8080/components/tex-element/`, where `tex-element` is the name of the directory containing it.

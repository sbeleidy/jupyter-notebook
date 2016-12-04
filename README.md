# \<jupyter-notebook\>

[![Join the chat at https://gitter.im/sbeleidy/jupyter-notebook](https://badges.gitter.im/sbeleidy/jupyter-notebook.svg)](https://gitter.im/sbeleidy/jupyter-notebook?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A web component to embed Jupyter notebooks - wrapper for [notebookjs](https://github.com/jsvine/notebookjs).

## Installing \<jupyter-notebook\>

`bower install jupyter-notebook --save`

## Using \<jupyter-notebook\>

<!--
```
<custom-element-demo>
  <template>
      <link rel="import" href="jupyter-notebook.html">
    <next-code-block></next-code-block>
  </template>    
</custom-element-demo>
```
-->
```
    <jupyter-notebook src="Demo.ipynb"></jupyter-notebook>
```


or
<!--
```
<custom-element-demo>
  <template>
      <link rel="import" href="jupyter-notebook.html">
    <next-code-block></next-code-block>
  </template>    
</custom-element-demo>
```
-->
```
  <jupyter-notebook src="https://raw.githubusercontent.com/fonnesbeck/pytenn2014_tutorial/master/Part%202.%20Statistical%20Data%20Modeling.ipynb"></jupyter-notebook>
```

If linking to a notebook file on GitHub, make sure you link to the raw file as shown above.

## Contributing

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### Viewing The Component

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

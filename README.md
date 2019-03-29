# babel-plugin-simple-js
Enforce a simple subset of JS

## What it does
*TODO* Removes the following keywords:

```
class
new
instanceof
super
this
void
private
public
static
*.prototype
Object
```



## Install

```
npm i --save-dev babel-plugin-simple-js
```

## Usage

1. Add the plugin to your .babelrc
2. Name any Simple JS files to end with ```.simple.js```

Example .babelrc:

```
{
  "presets": ["env"],
  "plugins": ["simple-js", "transform-object-rest-spread"]
}
```

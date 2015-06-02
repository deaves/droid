# Contributing

Some tips on how to contribute most effectively.

## Styling

The LESS files are automatically compiled into CSS files -- so don't edit any CSS files, edit LESS files instead. LESS is a superscript of CSS, so you can just write CSS inside the LESS files and you'll be fine.

## Adding new modules

To add a Bower module:

```
bower install --save [module]
```

To add a Node module:

```
npm install --save [module]
```

if the module is for needed for production, and

```
npm install --save-dev [module]
```

if the module is needed for development. Most likely you'll use the former.
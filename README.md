# Custom - Magento 2 theme
This theme has been created as a practice project for Magento 2 theme development. It mimics look and feel of web shop [Gigatron](https://gigatron.rs/).

### Instalation
Theme should be on path:
`.../app/design/frontend/Isidora/custom`

### Grunt setup
This should bee added at the end of file `...dev/tools/grunt/configs/local-themes.js`
```
  custom: {
    area: 'frontend',
    name: 'Isidora/custom',
    locale: 'en_US',
    files: [ 'css/styles-m', 'css/styles-l' ],
    dsl: 'less'
  }
```

### Licence
MIT
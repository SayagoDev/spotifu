- [Curso Flexbox Layout](#curso-flexbox-layout)
  - [Convenciones de nombre populares en CSS](#convenciones-de-nombre-populares-en-css)
  - [Convenciones para el curso](#convenciones-para-el-curso)
    - [Convenciones Generales](#convenciones-generales)
    - [Convenciones para CSS](#convenciones-para-css)
  - [Flexbox Containers](#flexbox-containers)
    - [Flex Layout Box Model](#flex-layout-box-model)

# Curso Flexbox Layout

## Convenciones de nombre populares en CSS

**BEM**
```
.block
.my-block
.my-block__element
.my-block__fancy-element
.my-block__element--modifier
```

**BEM ISSUES**
```html
<div class="my-component__element-fancy--fancy-modifier">

</div>
```

**SuitCSS**
```
MyComponent (Pascal Case)
MyComponent-part
MyComponent-anotherPart (Camel Case)
MyComponent--modifier
is-state
u-utility
```

## Convenciones para el curso

### Convenciones Generales
* No se escribirán estilos globales a excepción
  de las configuraciones y theme de la aplicación.
* Las clases serán basadas en componentes y no se deberán
  repetir.
* Una hoja de estilos por componente.
* Los componentes no deben tener dependencias externas.
* Los archivos se escribirán en **_kebab-case_**

### Convenciones para CSS
```
.component
.myComponent
.myComponent-part
.myComponent-anotherPart
.is-state
```

```html
<div class="myComponent-title is-hidden">

</div>
```

## Flexbox Containers

* `display:flex`
* `display:inline-flex`

### Flex Layout Box Model
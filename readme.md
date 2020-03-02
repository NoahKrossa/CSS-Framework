# CSS FRAMEWORK
-------------
## Guia de desarrllo
> Se empementará metodología <a href="#">BEM</a> para la nomeclatura de clases

> La estructura de archivos se basará en <a>SMACSS</a>

> El desarrllo se hará en <code>SASS</code> usando la extension <code>*.scss</code> 

### Estructura dentro de src/

+ Base/
    + _config.scss (archivo de configuración global)
    
    + _reset.scss

    + utilities/ (conjunto de clases atomicas con proposito unico)
        + _u_heading.scss (clases de heading)
        + _u_background.scss (<code>.bg--red, bg-black</code>)
        + _u_padding.scss
        + . . .
        + mixins/
+ Modules/
    + _m-button.scss
    + _m-modal.scss
    + _m-dropdown.scss
    + ...
+ Theme/
+ States/
    + _s-global.scss
    + _s-button.scss
    + ...
+ Layout/
+ main.scss
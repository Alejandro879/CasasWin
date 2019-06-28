# Documento de estilos

_Esplicacion sobre los estilos usado en casWin_

## Botones 🚀

_Se listan los botones con su respectivos codigo CSS._



### Ver Mapa 

![Click aca para ver imagen](https://alejandro879.github.io/CasasWin/assets/img/tutocss/vermapa.PNG)

* Codigo HTML 

```
<div class="boton-ver-mapa">
	<a class="hvr-overline-reveal" href="javascript:;" title="">Ver mapa</a>
</div>

```

* Codigo CSS

```
.boton-ver-mapa{
    position: relative;
    height: 34px;
    background: aliceblue;
    overflow: hidden;
    width: 153px;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    text-align: center;
    border-radius: 20px 0px 0px 20px;
    transition: all .7s;
}


```

```
.boton-ver-mapa:hover {
    background: #f8be30!important;
    color: white!important;
}


```

```
.boton-ver-mapa  >  a.hvr-overline-reveal {
    text-align: center;
    margin: auto;
    color: #000000cc;
    font-size: 18px;
    font-weight: 600;
}


```

### Menu Principal

![Click aca para ver imagen](https://alejandro879.github.io/CasasWin/assets/img/tutocss/menu.PNG)
 
* Codigo HTML 

```
<button class="animated fadeInLeftBig  link" type="button"> Lee un snack 
	<img alt="" class="galleta " src="./assets/img/logos/Galleta.png">
</button>

```

* Codigo CSS

```
#btn-menu-principal{
    border: 3px solid white;
    border-left: 0px;
    background: #75365d;
    outline: none;
    height: 57px;
    display: inline-block;
    width: 200px;
    border-radius: 0px 30px 30px 0px;
    color: white;
    font-weight: 600;
    margin: 8px 0px;
    text-align: left;
    padding-left: 17px;
    transition: all .4s;
}

```

```
#btn-menu-principal:hover {
    background: #f8be30!important;
    color: white!important;
}

```

### Enviar Correo

![Click aca para ver imagen](https://alejandro879.github.io/CasasWin/assets/img/tutocss/enviarcorreo.PNG)

* Codigo HTML 

```
<button class="btn btn-info btn-block link" type="submit">Submit</button>

```

* Codigo CSS

```
.boton-correo {
    width: 200px;
    margin: auto;
    border-radius: 20px;
    background-color: #cfab1e!important;
    border-color: #cfab1e!important;
    box-shadow: 1px 2px 3px #cfab1e14, 1px 5px 5px #cfab1e;
}

```

```
#btn-menu-principal:hover {
    background: #f8be30!important;
    color: white!important;
}

```

## Cajon Busqueda

_CSS Cajones de busquedas._

## Cajon header

![Click aca para ver imagen](https://alejandro879.github.io/CasasWin/assets/img/tutocss/cajonBusqueda.PNG)

* Codigo HTML 

```
<div class="rel">
   <span class="search-icon"><i class="ti-search"></i></span>
   <input class="form-control ui-autocomplete-input" id="tags2" placeholder="Busca aquí..." type="search" autocomplete="off">
</div>

```

* Codigo CSS

```
.rel, .p-relative {
    position: relative !important;
}

```

```
.header .navbar-search .search-icon {
    position: absolute;
    top: 0;
    left: 47px;
    height: 100%;
    width: 40px;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    color: #6d7c85;
}

```


```
.header .navbar-search .form-control {
    border: 0;
    padding: .65rem 1.25rem .65rem 40px;
    border-radius: 200px !important;
    background-color: #f4f5f9;
    border-color: #f4f5f9;
    font-size: 13px;
}

```

## Cajon home

![Click aca para ver imagen](https://alejandro879.github.io/CasasWin/assets/img/tutocss/cajonBusqueda.PNG)

* Codigo HTML 

```
<div class="contenido buqueda ">
    <input id="tags" name="" placeholder="¿Donde buscas tu proxima inversion?" type="search" value="" class="ui-autocomplete-input ng-pristine ng-valid ng-touched" autocomplete="off" ng-reflect-name="" ng-reflect-model="">
    <img alt="" class="link" src="./assets/img/logos/buscar.png">
</div>
```

* Codigo CSS

```
.contenido-a .contenido.buqueda {
    margin-left: 20px;
    height: 33px;
}

```

```
.contenido-a input[type="search"] {
    color: white;
    background: transparent;
    border: 3px solid white;
    width: 350px;
    padding: 7px 8px;
    font-weight: 600;
    border-radius: 33px 0px 0px 33px;
    display: block;
    font-size: 18px;
    text-align: center;
}

```


```
#cont-invoce .contenido-a .contenido.buqueda img {
    margin-left: 20px;
    height: 33px;
}

```

## Fondos

_CSS Fondo: Por lo general se trabajo en fondo pagina #fff solo explicamos lo que se modifico._

### Pantalla home



![Click aca para ver imagen](https://alejandro879.github.io/CasasWin/assets/img/tutocss/fondo.PNG)


* Codigo HTML 

```
<div class="page-heading" id="cont-invoce">
  
</div>
```

* Codigo CSS

```
#cont-invoce {
    background: rgba(41,131,167,0.85);
    background: radial-gradient(at center center, #2983a885 0%, rgba(41, 131, 168, 0.85) 55%, rgb(41, 131, 168) 100%);
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#2983a7', endColorstr='#7bb1ef', GradientType=1 );
    min-height: 100vh;
}
```

```
.page-heading {
    padding: 0 5px;
}

```


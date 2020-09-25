# Pinterest-Layout
Pinterest Layout

<p>
    <img src="https://res.cloudinary.com/dzgd10ssq/image/upload/v1599334917/Apps/ibqwa5ijh1opbo9phzks.gif" width="200"/ hspace="5"> 
</p>


# Comenzando 🚀

Estas instrucciones te permitirán obtener una copia de la aplicacion para propósitos de desarrollo y pruebas.

## Pre-requisitos 📋

Que plugins necesitas para el funcionamiento de la aplicacion
- [flutter_staggered_grid_view](https://pub.dev/packages/flutter_staggered_grid_view#-readme-tab- "flutter_staggered_grid_view")

Para personalizar el widget, se le envía los siguientes parámetros:

```
PinterestMenu(
            mostrar: mostrar,
            activeColor: Color(0xffc8232c),
            inactiveColor: Colors.blueGrey,
            backgroundColor: Colors.white,
            items: [
              PinterestButtom(icon: Icons.pie_chart, onPressed: (){print('piechart');}),
              PinterestButtom(icon: Icons.search, onPressed: (){print('search');}),
              PinterestButtom(icon: Icons.notifications, onPressed: (){print('notifications');}),
              PinterestButtom(icon: Icons.supervised_user_circle, onPressed: (){print('supervised');}),
            ],
          )
  ```
  
  En **ítems** se envía el icono del elemento del menú y la acción que debe realizar cuando se presiona.

# Construido con 🛠️
  - [Flutter](https://flutter.dev/ "flutter")
  - [Visual Studio Code](https://code.visualstudio.com/ "Visual Studio Code")
  - [unDraw](https://undraw.co/ "unDraw")

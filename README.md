# Proyecto final del curso de Javascript flex de CODER-HOUSE
## Alumno: Elias Escalante
## Profesor: Ezequiel Madrid
## Tutor: Maximiliano Salas 
## Comision: 61995

----

## Descripcion

- Mi proyecto simula un e-comerce que vende elementos de entrenamientos para artes marciales.
- El comercio tiene una variedad de productos que se pueden comprar
- El usuario puede agregar productos al carrito, eliminarlos y ver el total de la compra mientras agrega productos al carrito.
- Se agregan los productos al carrito luego se presiona el boton de comprar.
- El boton comprar lanza una ventana emergente con dos campos para completar (nombre y e-mail).
- Al presionar "continuar", lanza otra ventana con un mensaje con el nombre ingresado y el mail, a donde se envia el link de pago y las instrucciones de la compra.
- En la ventana, al presionar "confirmar", ademas de emitir el mensaje de compra mas la informacion ingresada, tambien informa el monto total de la compra que se realizo.

----

## Comentarios sobre el proyecto: 

- **Estructura**: El proyecto utiliza HTML para la estructura básica y CSS para el estilo y la presentación de la información.
- **Interactividad**: Toda la información y los eventos se gestionan e insertan en el HTML mediante JavaScript.
- **Validación de datos**: Utilicé expresiones regulares (regex) para validar el campo del correo electrónico.
- **Ventanas emergentes**: Utilicé la librería SweetAlert2 para las ventanas emergentes.
- **Gestión del carrito**: El botón "Comprar" desaparece si no hay elementos en el carrito, ya sea porque no se han agregado productos o porque se han eliminado todos.
- **Proceso de compra**: No se puede presionar "Ir a pagar" si no se completan todos los datos requeridos para la compra.
- **Finalización de compra**: Al completar la compra, tanto el carrito como el LocalStorage se vacían.
- **Persistencia del carrito**: Si se cierra accidentalmente la ventana, el carrito se guarda en el LocalStorage, permitiendo que se recupere al volver a abrir la página.
- **Manejo de errores**: Utilicé sentencias try para capturar y gestionar errores.
- **Responsividad**: Utilicé CSS nativo y diseñé el index.html para que sea responsive.
- **base de datos** Se utilizo un archivo json para simular la base de datos, este archivo almacena los productos que se venden en la pagina. y desde el archivo se insertan los productos en el html.
 
 ---

# Link a pages: https://eliasescalante.github.io/entrega_final_js/

---

# preview del sitio

![Texto alternativo](https://github.com/eliasescalante/entrega_final_js/blob/main/assets/capture_1.JPG)
![Texto alternativo](https://github.com/eliasescalante/entrega_final_js/blob/main/assets/capture_2.JPG)
![Texto alternativo](https://github.com/eliasescalante/entrega_final_js/blob/main/assets/capture_3.JPG)

# preview del sitio en mobile

![Texto alternativo](https://github.com/eliasescalante/entrega_final_js/blob/main/assets/capture_responsive_1.JPG) 
![Texto alternativo](https://github.com/eliasescalante/entrega_final_js/blob/main/assets/capture_responsive_2.JPG)
![Texto alternativo](https://github.com/eliasescalante/entrega_final_js/blob/main/assets/capture_responsive_3.JPG)
![Texto alternativo](https://github.com/eliasescalante/entrega_final_js/blob/main/assets/capture_responsive_4.JPG)
----
![GitHub repo size](https://img.shields.io/github/repo-size/eliasescalante/entrega_final_js
)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/eliasescalante/entrega_final_js
)
![GitHub last commit](https://img.shields.io/github/last-commit/eliasescalante/entrega_final_js
)


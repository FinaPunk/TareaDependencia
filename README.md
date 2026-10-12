clase Calculadora: se encarga de hacer operaciones matemáticas, como sumar y multiplicar dos números.
clase CarroCompra: guarda los datos de los productos, calcula sus subtotales y obtiene el total de la compra.

Relación entre clases:
entre CarroCompra y Calculadora existe una dependencia ya que en la clase CarroCompra existe el metodo private int subTotal(int cant, int precio)
que instancia la clase Calculadora para ocupar el metodo multiplicar().

Diagrama UML

<img width="537" height="184" alt="DiagramaTareaDependencia" src="https://github.com/user-attachments/assets/5f26b22c-b166-47a4-852a-55e99f496582" />

Programa ejecutado

<img width="1299" height="706" alt="EjecucionTareaDependencia" src="https://github.com/user-attachments/assets/0523c006-95b1-457b-acf1-0bde78cd2861" />

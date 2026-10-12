clase Calculadora: se encarga de hacer operaciones matemáticas, como sumar y multiplicar dos números.
clase CarroCompra: guarda los datos de los productos, calcula sus subtotales y obtiene el total de la compra.

Relación entre clases:
entre CarroCompra y Calculadora existe una dependencia ya que en la clase CarroCompra existe el metodo private int subTotal(int cant, int precio)
que instancia la clase Calculadora para ocupar el metodo multiplicar().


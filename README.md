# psp


## Clase
Qué es una Clase en Java?
Una clase en java es una plantilla (que puede estar diseñada por nosotros mismos o venir ya creada) para la creación de objetos, en lo que se conoce como programación orientada a objetos, la cual es una de los principales paradigmas de desarrollo de software en la actualidad. Como por ejemplo:
```Java
public class Persona{

  }
  ```

## Objeto
Qué es un objeto en Java?
Un objeto es la instancia de una clase. Si una tenemos una clase Perro los objetos serían sus atributos: el color, el nombre, la raza, etc...
Los objetos también pueden ser métodos como por ejemplo: ladrar, comer, etc...
```Java
public static color;
public static void ladrar(){}
```
## Sobrecarga de métodos
La Sobrecarga de métodos en java es la manera de reutilizar métodos de manera óptima en una misma clase, haciendo que un mismo método tenga diferentes usos.
```Java
public static void dormir(Class gato){
  String s="Boca arrriba";
}
public static void dormir(Class perro){
  String s="Boca abajo";
}
```
Para gato será boca arriba y para perro será boca abajo.
## Herencia
La herencia nos permite crear clases y que estas puedan compartir algunos de sus atributos de manera jerárquica, y solo de manera descendente, es decir, si tenemos la siguiente estructura:coche>deportivo/monovolumen; deportivo y monovolumen serán parte de la clase coche y podremos tener coches deportivos y monovolumenes pero no coches en sí.
```Java
public abstract Coche {

}
public Deportivo extends Coche{

}
public Monovolumen extends Coche{

}
```
## Polimorfismo
El Polimorfismo es lo mismo que la Sobrecarga salvo que para ser Sobrecarga, el método debe ser llamado varias veces desde una misma clase y el Polimorfismo.
## Interface
Una interfaz es una clase donde metemos solo métodos, como una libreria de creación propia.

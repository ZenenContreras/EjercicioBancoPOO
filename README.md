# EjercicioBancoPOO

        1. Principios SOLID
        Primero, asegúrate de entender los principios SOLID, ya que son fundamentales para este ejercicio:

        Single Responsibility Principle (Principio de Responsabilidad Única): Cada clase debe tener una sola responsabilidad.
        Open/Closed Principle (Principio de Abierto/Cerrado): Las entidades de software deben estar abiertas para extensión, pero cerradas para modificación.
        Liskov Substitution Principle (Principio de Sustitución de Liskov): Los objetos de una clase derivada deben poder reemplazar a los de la clase base sin afectar la correcta ejecución del programa.
        Interface Segregation Principle (Principio de Segregación de Interfaces): No se debe obligar a los clientes a depender de interfaces que no utilizan.
        Dependency Inversion Principle (Principio de Inversión de Dependencia): Depender de abstracciones, no de implementaciones concretas.
        
        2. Diseñar la Arquitectura
        Una arquitectura de capas:

        Capa de Dominio: Incluye las clases de negocio (CuentaBancaria, Cliente, etc.).
        Capa de Persistencia: Gestiona el almacenamiento de datos. Puedes tener dos implementaciones diferentes ( una base de datos y un archivo).
        Capa de Interfaz de Usuario: Dos interfaces diferentes para interactuar con el usuario ( una interfaz de línea de comandos y una interfaz gráfica).
        
        3. Implementar las Clases de Dominio
        Crea clases que representen las entidades de tu banco.

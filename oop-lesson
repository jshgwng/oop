
### 1. Classes and Objects:

#### Definition:
A class is a blueprint or a template for creating objects. It defines the attributes and behaviors common to all objects of that type. An object is an instance of a class, representing a real-world entity.

#### Example:
```java
// Class definition
class Car {
    String brand;
    int year;

    // Method
    void start() {
        System.out.println("Car started!");
    }
}

// Creating objects
Car myCar = new Car();
myCar.brand = "Toyota";
myCar.year = 2022;
myCar.start();
```

In this example, `Car` is a class with attributes (`brand` and `year`) and a method (`start`). An object `myCar` is created based on this class, and its attributes are set and a method is called.

### 2. Encapsulation:

#### Definition:
Encapsulation is the bundling of data (attributes) and methods that operate on the data into a single unit (class). It helps in data hiding and protects the internal state of an object.

#### Example:
```java
class BankAccount {
    private double balance;

    // Method to deposit
    public void deposit(double amount) {
        balance += amount;
    }

    // Method to get balance
    public double getBalance() {
        return balance;
    }
}
```

In this example, `balance` is encapsulated within the `BankAccount` class. The `deposit` method allows modifying the balance, and the `getBalance` method provides controlled access to the balance.

### 3. Inheritance:

#### Definition:
Inheritance allows a class (subclass or derived class) to inherit the properties and behaviors of another class (superclass or base class). It promotes code reuse and establishes a relationship between classes.

#### Example:
```java
class Animal {
    void eat() {
        System.out.println("Animal is eating");
    }
}

class Dog extends Animal {
    void bark() {
        System.out.println("Dog is barking");
    }
}
```

Here, `Dog` inherits from `Animal`. The `eat` method is inherited, and `Dog` adds a new method `bark`. Objects of `Dog` class can use both `eat` and `bark` methods.

### 4. Polymorphism:

#### Definition:
Polymorphism allows objects of different classes to be treated as objects of a common superclass. It enables methods to be used interchangeably based on the context.

#### Example:
```java
class Shape {
    void draw() {
        System.out.println("Drawing a shape");
    }
}

class Circle extends Shape {
    void draw() {
        System.out.println("Drawing a circle");
    }
}

class Square extends Shape {
    void draw() {
        System.out.println("Drawing a square");
    }
}
```

In this example, `Shape` is a superclass with a `draw` method. Both `Circle` and `Square` are subclasses that override the `draw` method. Polymorphism allows calling `draw` on any object of type `Shape` without knowing its specific subclass.

### 5. Abstraction:

#### Definition:
Abstraction involves hiding the complex implementation details and showing only the necessary features of an object. Abstract classes and interfaces are used to achieve abstraction.

#### Example:
```java
abstract class Shape {
    abstract void draw();
}

class Circle extends Shape {
    void draw() {
        System.out.println("Drawing a circle");
    }
}
```

`Shape` is an abstract class with an abstract method `draw`. Concrete subclasses like `Circle` provide specific implementations. Users can work with the abstraction (`Shape`) without worrying about the details of each shape.

### 6. Interfaces:

#### Definition:
An interface is a collection of abstract methods. A class can implement one or more interfaces. It provides a way to achieve multiple inheritance in Java.

#### Example:
```java
interface Printable {
    void print();
}

class Document implements Printable {
    public void print() {
        System.out.println("Printing document");
    }
}
```

In this example, `Printable` is an interface with a `print` method. The `Document` class implements this interface, providing the actual implementation of the `print` method.

# Car and ElectricCar Java Classes

This repository contains two Java classes that demonstrate the principles of object-oriented programming (OOP), specifically encapsulation and inheritance. The `Car` class represents a general car, while the `ElectricCar` class extends it to represent an electric car with additional properties.

---

## Files

### **Car.java**
- **Purpose**: Models a general car with basic attributes and methods to encapsulate and manipulate data.
- **Features**:
  - Encapsulated fields: `brand`, `model`, `year`.
  - Getter and Setter methods to access and modify private fields.
  - Constructor to initialize a `Car` object with specific values.
  - Method `displayCarDetails()` to print the car's details.
- **Concepts Demonstrated**:
  - **Encapsulation**: Protects data using private fields and public getters/setters.
  - **Object Creation**: Demonstrates creating and manipulating a `Car` object.

#### Example Usage
```java
Car myCar = new Car("Toyota", "Corolla", 2021);
System.out.println("Brand: " + myCar.getBrand());
myCar.displayCarDetails();
myCar.setModel("Camry");
System.out.println("Updated model: " + myCar.getModel());

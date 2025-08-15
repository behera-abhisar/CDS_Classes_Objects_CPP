## THEORY

In C++, a **class** is a user-defined data type that acts as a blueprint for creating objects. It encapsulates data members (variables) and member functions (methods) into a single unit, enabling the principles of **Object-Oriented Programming (OOP)** such as **encapsulation**, **abstraction**, **inheritance**, and **polymorphism**.

- **Data Members** – Variables that hold the state (attributes) of the object.
- **Member Functions** – Functions that operate on the data members and define the behavior of the object.

An **object** is an instance of a class. Multiple objects can be created from the same class, each with its own separate copy of the class's non-static data members but sharing the same structure and behavior.

**Key Characteristics:**
1. **Encapsulation** – Bundling of data and functions into a single unit to protect internal states.
2. **Access Specifiers** – Control how members are accessed:
   - `public` – Accessible from anywhere.
   - `private` – Accessible only within the class.
   - `protected` – Accessible within the class and derived classes.
3. **Constructor** – A special function with the same name as the class, automatically called when an object is created, used for initialization.
4. **Destructor** – A special function with the same name as the class prefixed by `~`, automatically called when an object is destroyed, used for cleanup.
5. **Member Function Definition** – Can be done inside the class (inline) or outside the class using the scope resolution operator `::`.

---

### **Generic Syntax of a Class in C++**

```cpp
class ClassName {
private:
    // Private data members

public:
    // Public data members

    // Constructor
    ClassName();

    // Destructor
    ~ClassName();

    // Member functions
    void functionName();
};

# Hospital-Management-System
About Hospital Management System using Object Oriented Programming in C++. Demonstrated Inheritance, Polymorphism, Abstraction &amp; Data hiding OOP principles .Implemented Exception Handling and File Handline; used Virtual Base Class and Friend functions

Object Oriented Programming
Object-oriented programming is essentially a concept or technique for computer programming that models software architecture around data or objects rather than functions and logic.A data field is referred to as an object if it has distinct characteristics and behaviour. In OOP, everything is categorised as objects.


Among developers, it is the most often used programming paradigm. Large, complicated, and actively updated or maintained programmes work well with it. It provides fundamental ideas like abstraction, inheritance, polymorphism, and encapsulation, which make programme creation and maintenance easier. These fundamental ideas define OOP.

User-defined data types called classes serve as the building blocks for specific objects, properties, and methods. Objects are instances of a class that were generated using data that was defined. Objects can be an abstract concept or a real-world thing. 

Classes and Objects:

Classes serve as blueprints for real-world entities within the hospital environment. Examples include Patient, Doctor, Nurse, Appointment, Department, Bill, Medicine, etc. Objects are instances of these classes, representing actual patients, doctors, appointments, and so on, each with their unique data and behaviors. Example: A Patient object might have attributes like name, patientID, age, medicalHistory, and methods like getsAdmitted(), undergoesTreatment(). A Doctor object might have name, doctorID, specialization, workingHours, and methods like checksPatient(), prescribesMedication(). Encapsulation:

Data and the methods that operate on that data are bundled together within classes. This ensures data integrity by preventing direct external access to an object's internal state. Access to attributes is typically controlled through public methods (getters and setters), allowing for validation and controlled modification. Example: A Patient object's medicalHistory might be private, only accessible and modifiable through methods like addMedicalRecord() or getMedicalHistory(), ensuring that medical data is handled securely and consistently. Inheritance:

Common attributes and behaviors are extracted into base (parent) classes, and specialized classes (child classes) inherit from them. This promotes code reusability and establishes a clear hierarchy. Example: A Person base class could have common attributes like name, age, gender, address. Patient, Doctor, and Staff could inherit from Person, each adding their specific attributes and methods (e.g., Patient adds patientID, medicalHistory; Doctor adds specialization, doctorID). Polymorphism:

"Many forms" - allows objects of different classes to be treated as objects of a common superclass. This enables flexible and extensible code. Method Overriding: Child classes provide their specific implementation for a method already defined in their parent class. Example: A Person class might have a generic displayDetails() method. Patient, Doctor, and Staff classes could override this method to display details relevant to their specific roles (e.g., Patient displays patientID and medicalHistory, Doctor displays specialization and workingHours). Virtual Functions (in C++ context): Used to achieve runtime polymorphism, allowing the correct method implementation to be called based on the actual object type at runtime, even when accessed through a base class pointer or reference.

Focuses on showing only the essential information and hiding the complex implementation details. This is achieved through abstract classes and interfaces. Example: An abstract User class might define common operations like login() and logout(), without specifying how each specific type of user (Admin, Doctor, Patient) implements these. The concrete Admin, Doctor, and Patient classes would then provide their specific login() implementations.

Exception Handling
Exception handling in C++ consist of three keywords: try, throw and catch:

The try statement allows you to define a block of code to be tested for errors while it is being executed.
The throw keyword throws an exception when a problem is detected, which lets us create a custom error.
The catch statement allows you to define a block of code to be executed, if an error occurs in the try block.

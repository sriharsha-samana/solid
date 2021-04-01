- Single Responsiblity principle
  - A class should have a single responsibility
  - A class should have one, and only one reason to change

- Open Close principle
  - A class should be open for extension but closed for modification
  
- Liskov Substitution
  - Every sub-class should be substitutable to it's parent class
  - Derived classes must be usable through the base class interference, without the need for the user to know the difference
  
- Interface Segregation
  - Dependencies should not be forced on objects that do not use them
  - Too many interfaces are better than too little
  - This allows to split the responsibility of a class without LSP violation
  
- Dependency Inversion
  - Objects must depend on abstractions rather than concretions

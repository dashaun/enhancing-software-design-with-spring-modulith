### Modulith?

Modular monoliths

Notes:
- are a new way to organize and evolve software projects.
- They are a hybrid approach
- combines the benefits of microservices
- with the simplicity of monolithic architectures. 
- Moduliths are designed to be highly modular,
- with each module encapsulating a specific set of functionality.
- This makes it easier to reason about the codebase, maintain and evolve the software,
- and scale the application as needed.

---

### Efficiently organize and evolve software projects

Notes:
- Look at xyz.gofastforever.account
- We have two modules
- Inventory and Orders
- Inventory depends on Orders
- Not fancy, nothing special

---

### Defining and managing logical modules

Notes:
- Look at xyz.gofastforever.account
- We have two modules
- Inventory and Orders
- Inventory depends on Orders
- Not fancy, nothing special

---

### Utilizing tools for structural validation tests

Ensuring each component functions correctly and cohesively.

- ArchUnit
- https://archunit.org/

Notes:
- Defaults included
- Can be modified
- Can be verified
- verifiesModularStructure() test

---

### Documenting the architecture of your application

Facilitating better collaboration and future modifications

Notes:
- PlantUML
- C4 Model
- Asciidoctor
- Plays nice if you are using Spring REST docs
- renderDocumentation() test

---

### Implementing interactions between modules in a way that maintains their independence

Yet allows for effective communication

Notes:
- No additional clients
- No additional contracts
- Event-driven
- Domain-driven
- Start with the Spring Application Context
- Eventing built-in
- look at OrderManagement.complete

---

### Monitoring real-time interactions between modules during the software's operation

Notes:
- http://localhost:8080/actuator
- 
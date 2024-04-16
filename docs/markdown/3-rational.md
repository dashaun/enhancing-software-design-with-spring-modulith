### Onboarding

Make the right thing to do, the easy thing to do

Notes:
- Accelerate the onboarding process
- Formalize the process
- Simplify the process

---

### Scaling

- Microservices allow independent scaling
- Do you need that on Day 1?

---

### Patching

- Patching is a critical part of the software development lifecycle
- (Spring Boot 3.3 coming May 23rd)
- Every repository needs to be maintained


Notes:
- When the next version of Spring Boot comes out
- How many repositories need patching?

---

### Documenting

- Test Driven Documentation is the other TDD
- Do you need to open your IDE to understand the repo?
- Do you document the relationships between your microservices?

Notes:
- Spring REST docs (OpenAPI)
- Documentation driving the code

---

### Testing Slices

- @DataJpaTest
- @WebMvcTest
- @JdbcTest
- @DataMongoTest
- @JsonTest
- @RestClientTest

Notes:
- Slices are awesome
- write tests for specific parts of your application
- in isolation
- without bootstrapping the whole Spring Context

---

### Getting to Production

- Software supply chains
- Artifacts
- Distributed systems

---

### Fallacies of Distributed Systems

- The network is reliable
- Latency is zero
- Bandwidth is infinite
- The network is secure
- Topology doesn't change
- There is one administrator
- Transport cost is zero
- The network is homogeneous

Notes:
- Remember, remember

---

### Day 2

- Maintenance
- Monitoring
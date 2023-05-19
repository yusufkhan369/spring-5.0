Any java class we write depends on other classes. 
The other classes a class depends on are its dependencies.
If a class directly creates instances of dependencies, a tight coupling is established between them.
With Spring, the responsibility of creating and wiring objects is taken over by a new component called the Inversion of Container.
It creates objects and wires dependencies together.
This revolutionary concept, where the control of creating and wiring dependencies is taken over by another container is called
dependency Injection
Below for beans which are to be created
@Repository
@Component
@Service
@Configuration to scan where the classes are to present as beans








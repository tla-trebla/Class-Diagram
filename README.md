# Class-Diagram

This learning is based from Design Patterns by Tutorials by Ray Wenderlich. Link: https://www.raywenderlich.com/books/design-patterns-by-tutorials

## Things I've Learned

* Class Diagram are based from Unified Modeling Language (UML).
* A box denotes as a class or protocol.
  * A protocol denoted by writing a `<<protocol>>` before its name.
* There are various of arrows to indicates a communication between class diagrams.
  * Inheritance / is a: Open arrowhead and straight line.
  * Property / has a: Plain arrowhead and straight line.
    * In property, to show 'has many', indicate with a `1 ... *` text besides arrowhead.
  * Implements protocol / conforms to: Open arrowhead and dashed line.
  * Dependency: Plain arrowhead and dashed line.
    * Dependency has various meaning, so it's better to write beside the line what does it communication do:
      * Weak property or delegate.
      * Object passed as a parameter.
      * Loose coupling or callback.

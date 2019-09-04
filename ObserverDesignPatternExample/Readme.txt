- Obser Design Pattern -

What:
A Observer Design pattern is a behaviour pattern.

Why:
Encapsulate creating objects and easily expandable.

How:
Define a one-to-many dependency between objects (Subject => Observers) so that when one object (the Subject) changes state, 
all its dependents (Observers) are notified and updated automatically.

Real World Examples:
- When the connection to a database fails "handle error on screen"/"mail admin"/etc classes are notified and updated.
- When an upgrade is collected in a game, "player score"/"GUI score"/etc classes are notified and updated.
- When an application with employees payes the employees their salary, "mail employees"/"mail CEO"/etc classes are notified and updated.
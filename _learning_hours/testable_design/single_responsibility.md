---
theme: testable_design
title: Single-responsibility Principle
kata: person
difficulty: 1
author: edytterbrink
affiliation: Chocolate Driven Development AB
---

# Single-responsibility Principle
The Single-responsibility Principle is the S in the SOLID principles, Coined by Robert C. Martin.
[Wikipedia on Single-responsibility Principle](https://en.wikipedia.org/wiki/Single-responsibility_principle)
It states that code should only have one reason to change, or one stakeholder that might initiate a change.

## Goal
Practise to separate out different aspects of a model, depending on who might use the information.

## Session outline

* 5 min connect: What makes testing hard(er)? 
* 15 min concept: The playground metaphor / SOLID principles / Too mant cooks spoil the broth
* 30 min concrete: Refactor the Person Kata with the single responsibility principle in mind.
* 10 min Conclude: What would be the effect if you used this more in your daily work?

### Concept
* The playground as a metaphor for code learning to behave in tests. 
Code that is tested, and used in production, has shown that it can behave in two contexts.
It is then also reusable. Testable code and well designed code is the same thing.
* SOLID principles
* Ask the team: How many SOLID principles can you name? 
* Single Responsibility principle
* Ask the team: When is a unit small enough? 
* Describe how it is about stakeholders. One person/role/reason/department/dependency who wants initiate change in the code.
(One version is described here: [Too many cooks spoil the broth (since everyone puts salt in it).](https://www.chocolatedrivendevelopment.com/2022/10/04/single-responsibility-salt/) )
* Look at the code in the Person Refactoring Kata.
* Ask the team: Who could initiate a change in Person? 
  * Suggestions: 
    * DBA
    * HR-software vendor 
    * the government
    * the sales manager
    * the engineer manager
    * technical advancement
    * notification service vendor
    * security department

### Concrete
Do the [Person Refactoring kata](https://github.com/sammancoaching/Person-Refactoring-Kata)
with the Single-responsibility principle in mind.

### Conclude
What would be the effect if you used this more in your daily work?

### Works well with
- [Primitive obsession](/learning_hours/refactoring/primitive_obsession.html)
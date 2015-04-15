
**Aggregates**: used for creating new pure Objects.
**Repository**: used for reconstruct object and store & retrieval from database.

**Modeling technique**: Read the business specifications and look for nouns and verbs. The nouns are converted the classes while the verbs become methods.

**Code fights you**: A stiff design resists refactoring. Code that wasn’t built with flexibility in mind so code hard to work with. Whenever change is needed, you will see the code fighting you.

**Breakthrough**: often involves a change in thinking. It is also a source of great progress in the project.
It can imply a large amount of refactoring
It may introduce behavioral changes in the application.

**Specification**: If Ubiquitous Language  specifically mentions the respective process then it is time for an explicit implementation. If evaluating rules on given object involves number of checkings which may involve business rules and other tons of different rules, it is time for use Specification.

##Preserving model Integrity

The first requirement of a model is to be consistent, with invariable terms and no contradictions.

**Unification**: Internal consistency of a model.

In order to preserve large unified model for the entire enterprise project, we should consciously divide it into several models. Each of the can evolve independently as long as they obey the contract they are bound to.

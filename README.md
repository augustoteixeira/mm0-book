# mm0-book

A book on logic and set theory based on mm0 (https://github.com/digama0/mm0)

# phylosophy

* Empower - people reading should feel like they could write it
* Familiar - notation/statements should mimic what mathematicians are used to.
  This helps with understanding the material, reduces learning curve, reduces feeling that
  formal methods are alien, thus improves empowerment.
* Mnemonic - people should not have to memorize thousands of things like syl6. For this:
  * Present fewer results (even if future proofs involve more steps).
  * Rely on familiarity to decide what to introduce (easier to remember familiar things)
  * Create patterns accross the book (for example, deduction style being always the same)
* Good choice of divisions (multiscale: book, chapter, section):
  * good encapsulation
  * small surface of interaction
  * DAG of dependencies
* Can be read skipping the tactics code, just learning what they do instead.

# Reading dependence DAG in mermaid

# Index

# TODO

* Split file into many:
  * Individual files with chapters/sections, tactics
  * Experimentations with mm1
* Organize how tactics should be presented
* Polish deduction tactics
* Use deduction tactics in Equivalence
* Try to make i -> d -> c theorem forms more uniform
* clean duplicated statements
* move mp_dd and syl_d down. Together with conjunction, a section on joining
  hypotheses. Explain that it is natural to join hypotheses or theses in conjunctions.
  Then give as an example the double deduction.
* conjunction + joining hypotheses
* disjunction + case analysis
* insert a deduction tactic chapter after disjunction? There is the issue that
  contracting a single hypotheses did not happen yet. But I don't see it as a big obstacle.
* equivalence is a much bigger section. Perhaps ending with a chapter about the substitution
  tactic.
* really do a section on truth tables ending with a tactic? Perhaps it is not as useful.
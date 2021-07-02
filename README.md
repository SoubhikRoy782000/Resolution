# Resolution

Aim -

To implement the resolution for a real world problem where we give input as a text file where a first order logic situation is described and by using command prompt we print the first order logic situation result.


Algorithm -

Step 1 – Conversion of facts into first-order logic.

Step 2 – Convert FOL statements into CNF

Step 3 – Negate the statement which needs to prove (proof by contradiction)

Step 4 – Print resolution solution.


Resolution - 

Resolution basically works by using the principle of proof by contradiction. To find the conclusion we should negate the conclusion. Then the resolution rule is applied to the resulting 
clauses. Each clause that contains complementary literals is resolved to produce a2. New clause, which can be added to the set of facts (if it is not already present). 

This process continues until one of the two things happen –

a) There are no new clauses that can be added

b) An application of the resolution rule derives the empty clause.

An empty clause shows that the negation of the conclusion is a complete contradiction, hence the negation of the conclusion is invalid or false or the assertion is completely valid or true.

1. Convert the given statements in Predicate/Propositional Logic

2. Convert these statements into Conjunctive Normal Form

3. Negate the Conclusion (Proof by Contradiction)

4. Resolve using a Resolution Tree (Unification)


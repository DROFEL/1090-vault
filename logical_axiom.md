- common sense assumptions of our logical system 
- we know they are true, and we use them to prove
- they are all [[formula_states#Tautology|Tautologies]]
- all [[hilbert_style_proofs|Hilber proofs]] begin with one of these axioms (or a part of the hypothesis), as they're assumed to be true.

![[logical_axioms.png]]
#TODO: fill this part out

| axiom number | what it means                                                                                            | 
| ------------ | -------------------------------------------------------------------------------------------------------- |
| 1            | Nested equivalence statements can be compared in any order                                                                                                        |
| 2            | Equivance is symmetrical, dosen't matter what side the parts are on.                                                                                                         |
| 3            | $\top$ and $\bot$ aren't equivalent, and return $\bot$                    |
| 4            | if $\neg A$ is false and A is true then they aren't equivalent, $\therefore$ $F \equiv \bot$ is true.    |
| 5            |                                                                                                          |
| 6            |                                                                                                          |
| 7            | an $\lor$ with  two of the same variables being compared will return the [[truth_value]] of the variable |
| 8            |  $A\lor$ can be distributed into nested comparisons|
| 9            | A or $\neg A$ always returns true, as one of them is always true                                         |
| 10           | if $A$ and $B$ are true, then $A\land B$ and $A\lor B$ are equivalent                                                                                                        |
| 11           |                                                                                                          |

### Other Axioms 
Distributivity of $\land$ over $\lor$
$(A\rightarrow B) \equiv (\neg A \lor B)$

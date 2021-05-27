1. Start.
2. Create structure for production with LHS and RHS.
3. Open file and read input from file.
4. Build state 0 from extra grammar Law S' -> S $ that is all start symbol of grammar and one Dot ( . ) before S symbol.
5. If the Dot symbol is before a non-terminal, add grammar laws that this non-terminal is in the Left Hand Side of that Law and set Dot in before the first part of Right Hand Side.
6. If a state exists (a state with this Laws and same Dot position), use that instead.
7. Now find a set of terminals and non-terminals in which Dot exists in before.
8. If step 7 Set is non-empty go to 9, else go to 10.
9. For each terminal/non-terminal in set step 7 create a new state by using all grammar laws that Dot position is before that terminal/non-terminal in reference state by increasing Dot point to the next part in the Right Hand Side of that law.
10. Go to step 5.
11. End of state building.
12. Display the output.
13. End.

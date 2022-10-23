# Part 1 Answers

1. values added:    20
2. final result:    20
3. values added:    20
4. `ReferenceError` – There's a reference error because `let` only allows the if-block to access the variable `result`, so the second log statement cannot reference it.
5. Line 9 prints *Cannot assign to "result" because it is a constant* since we cannot change the value of `result` after it is initialized.
6. Line 13 also prints the same error, but on top of that there is a `ReferenceError` because once again, the keyword `const` prevents access to the variable outside of the scope of the if-block.
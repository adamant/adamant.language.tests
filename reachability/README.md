# Borrow Checking Tests

Because the compiler's analysis runs in two phases, all the tests in here need to pass the first phase which is syntax, typing and ownership/moves. All errors should be from the borrow checker only. Otherwise there are issues where the borrow checking errors don't get reported.

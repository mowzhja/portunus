- [x] Prototype the thing to test feasibility
- [x] Build the core functionality
  - [x] Code up the locksmith
  - [x] Code up the librarian
- [x] Build the CLI interface
- [x] Make a function to handle tests in one line (be DRY)
- [x] Test, test, test (tests should be written as you write the code, but just make sure everything works well in this phase)
  - [x] Complete writing unit tests
  - [x] Write integration tests/test Cobra commands
  - [x] Check test coverage (there may be some special cases you missed)
- [x] Fix the monotonic clock reading problem (use .Round(0) when writing times to files, check the librarian_test.go)
- [x] Throw away Go key generation => automate ssh-keygen!
  - [x] Fix the broken tests in cmd/ and locksmith/
- [x] Notify the user of what portunus is doing at times (aka more prints and such)
- [x] Look into using colored print for extra coolness (<https://github.com/fatih/color>)
- [ ] Refine, refine, refine (optimize the code both stylistically and functionally)
  - [x] Look into splitting up librarian.go
  - [ ] Benches, maybe?
- [ ] Put the expiry data in a custom struct instead of using maps (maybe)
- [ ] Work on extra features (if any)

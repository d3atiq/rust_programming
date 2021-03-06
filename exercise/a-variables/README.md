# Exercise A: Variables

### Part 1
- [ ] Make a new project named `variables` using cargo
  - See "cargo help" if you forgot the command.
- [ ] Open `Cargo.toml`
  - Hopefully Rust was able to figure out your name and email address for you!
  - [ ] Change the version number to 2.3.4, just for fun, and save the file.
    Keep an eye out for that version number in cargo's output when you run it!
- [ ] In `src/main.rs`
  - [ ] Bind the variable `missiles` and initialize it to `8`
  - [ ] Bind the variable `loaded` and initialize it to `2`
- [ ] Change the `println!(...)` at the end of `main()` to:
  - `println!("Firing {} of my {} missiles...", loaded, missiles);`
- [ ] Run your program using cargo (see "cargo help" if you forgot the command).
  Some common errors you may hit:
  - Forgot to use `let` to bind a variable
  - Forgot a semicolon `;` at the end of each line

### Part 2

- [ ] After the first `println!(...)`, subtract `loaded` from `missiles` like this:
  - `missiles = missiles - loaded;`
- [ ] Add a second `println!(...)` to the end:
  - `println!("{} missiles left", missiles);`
- [ ] Run your program again using cargo
  - Did you run into an error about mutability?  Make sure you added `mut` to the right place.
- [ ] Once you have it working, copy and paste the 2 lines of output into the group chat.
- [ ] Nice. Congratulate yourself on a job well done.  You are a Rust programmer now!

### Extra challenges:
- [ ] Explicitly annotate the variables with the type `i32`
- [ ] Try binding the variables all at once on one line using a pattern (parenthesis and commas) -- can you figure out where "mut" goes?
  - [ ] Can you figure out the correct type annotation when you assign them all in one line? Hint: it will use the same sort of pattern.
- [ ] Instead of changing missiles, just print `missiles - loaded` in the second `println(...)`
  - What does cargo say when you run your program?  
- [ ] Add another variable to your program *but don't use it*.
  - What does cargo say when you run your program?  

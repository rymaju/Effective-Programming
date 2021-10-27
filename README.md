# Effective-Programming
A list of statements about programming that remind me how to write better code.

- Make everything immutable
- If your function is returning void, something is very wrong
- [Follow the damn design recipe](https://htdp.org/2021-5-4/Book/part_preface.html#%28part._sec~3asystematic-design%29)
- Purpose statements document intent. Only write them when the function name and body are not enough.
  - AKA: Comments go bad, try to avoid writing a lot of them.
- Code is a message to the future
- Dont be a 1970s programmer
- Test for testing's take
  - Tests are about working through examples and code organization, not just making sure that "it works".
- All code is flawed in one form or another, either functionally or in terms of design. To find flaws practice code walks.
- A good code walk involves hunting for suspicious or "ugly" code and asking questions to articulate why it seems "ugly".
- "Ugly" is just shorthand for a design flaw that isn't easy to articulate.
- [Data =/= Information](https://htdp.org/2021-5-4/Book/part_one.html#%28counter._%28figure._fig~3adata-info%29%29). Protect yourself from input, make the transformation between the two explicit.
- Readability of code is a function of the skill of the programmer, not the features of their chosen programming language.

# Conclusion of Ticket-101 - Frontend

---

Problems outside of scope for the Take Home Task will not be written in here such as the use of Git.

## Done Well

---

- A working application was build by the guidelines of the Ticket

- The test cases provided covered a wide range of cases. 

- Codebase is well written and understandable.  

- Multiple descriptive comments were given for all widgets and functions.  

- Integration between frontend and backend was well done, API requests are handled correctly.  


## Places For Improvement // Problems

---

- The main problem with the implementation of Ticket-101 is the fact that if a person applies for 4000€, but the engine determines that we would approve a larger sum, the engine then does not show the maximum sum, instead the engine shows the sum which the client asked for.  

- For each slider change, the frontend sends a request to the backend which should not be done for the danger of overloading the backend from requests.  

- The folder inbank-frontend-98f09aabec29a741365f750db29dfe606f20f0b2 has somehow been duplicated into the main folder, whether it be a working or temp folder, it should be removed.  

- While loans are typically calculated in 6 month periods, for someone who is not accustomed to them, It would seem like too large of a gap.  

- The month slider text started from 6 instead of 12.  

- The Dart linter shows multiple fix suggestions that should be looked at before pushing to git. Fixes like using Const for Rows and Columns, providing keys by using Super and using Expaned inside Stack instead of as a descendant of a Column, Row or Flex.  

- Mobile views could be done better, for example the title shouldn't dissapear.  

## Fixes

---

- Deleted the duplicate folder.  

- Month slider text changed.  

- Dart Linter fixes implemented.  

- Included the Ticket-101 task of showing the maximum loan sum based on the Credit Score, Modifier and Period.


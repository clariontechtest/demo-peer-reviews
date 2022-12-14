## C# Code Review Checklist

### General

- Applicable Access modifiers are made as private as possible
  - [ ] Yes
  - [ ] Not Applicable

### Maintainence

- All names are clear, descriptive and accurate. Clear naming is preferred over comments
  - [ ] Yes
  - [ ] Not Applicable
- Well-named enums are used instead of magic strings and numbers
  - [ ] Yes
  - [ ] Not Applicable
- Functions avoid side effects

  - [ ] Yes
  - [ ] Not Applicable

- Conditionals should be positive, not negative
  - [ ] Yes
  - [ ] Applicable
- Methods do not accept more than 3 parameters
  - [ ] Yes
  - [ ] Not Applicable
- All methods and classes do just one thing / follow SRP
  - [ ] Yes
  - [ ] Applicable
- SOLID principles are adhered to
  - [ ] Yes
  - [ ] Not Applicable
- All code has passed linting
  - [ ] Yes
  - [ ] Not Applicable
- Following [Clean coding priciple](https://knowledgebase.clariontechnologies.co.in/articles/c-coding-guideline-any-object-oriented-language)
  - [ ] Yes
  - [ ] Not Applicable

### Performance and Scalability

- Reviewer has stepped through all modified code paths using a performance data set to look for performance / memory / CPU usage issues
  - [ ] Yes
  - [ ] Not Applicable
- Appropriate data structures have been used
  - [ ] Yes
  - [ ] Not Applicable
- async / await is used for I/O bound code paths
  - [ ] Yes
  - [ ] Not Applicable

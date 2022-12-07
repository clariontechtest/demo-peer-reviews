Make sure these boxes are checked before submitting/approving the PR

# General
  - [ ] The code works
  - [ ] The code is easy to understand
  - [ ] Follows coding conventions
  - [ ] Names are simple and if possible short
  - [ ] Names are spelt correctly
  - [ ] Names contain units where applicable
  - [ ] There are no usages of [magic numbers](http://c2.com/cgi/wiki?MagicNumber)
  - [ ] No hard coded constants that could possibly change in the future
  - [ ] All variables are in the smallest scope possible
  - [ ] There is no commented out code
  - [ ] There is no dead code (inaccessible at Runtime)
  - [ ] No code that can be replaced with library functions
  - [ ] Variables are not accidentally used with null values
  - [ ] Variables are immutable where possible
  - [ ] Code is not repeated or duplicated
  - [ ] No complex/long boolean expressions
  - [ ] No negatively named boolean variables
  - [ ] No empty blocks of code
  - [ ] Ideal data structures are used
  - [ ] Constructors do not accept null/none values
  - [ ] Catch clauses are fine grained and catch specific exceptions
  - [ ] Exceptions are not eaten if caught, unless explicitly documented otherwise
  - [ ] Files/Sockets and other resources are properly closed even when an exception occurs in using them
  - [ ] `null` is not returned from any method
  - [ ] == operator and === (and its inverse !==) are not mixed up
  - [ ] Floating point numbers are not compared for equality
  - [ ] Loops have a set length and correct termination conditions
  - [ ] Blocks of code inside loops are as small as possible
  - [ ] No methods with boolean parameters
  - [ ] No object exists longer than necessary
  - [ ] No memory leaks
  - [ ] Code is unit testable
  - [ ] Test cases are written wherever possible
  - [ ] Methods return early without compromising code readability
  - [ ] Performance is considered
  - [ ] Loop iteration and off by one are taken care of
  
# Folder Structure
  - [ ] Is project following Clarion's default folder structure for PHP projects or any third party PHP framework (Laravel, Symfony, CakePHP etc)?
  - [ ] Does config.inc.php file under includes directory holds all the configuration constants of the site?




# Indenting and Line Length
  - [ ] Is opening php tag “<?php” and end tag “?>” at first column of the page?
  - [ ] Is single tab spacing followed for code indentation?



# Control Structures
  - [ ] Is opening braces for IF...ELSE, FOR, WHILE, SWITCH etc control structure on the same line along with one space added before the opening brace?
  - [ ] Does Control statements have one space between the control keyword and opening parenthesis?



# Function Calls and Definitions
  - [ ] Are functions called with no spaces between the function name, the opening parenthesis and the first parameter?
  - [ ] Are arguments with default values mentioned at the end of argument list?
  - [ ] Is opening braces placed at next line after the function definition?



# Comments
  - [ ] Is Comment added at start of each file as per PHP standards giving description of file along with other required parameters?



# Include Statements
  - [ ] Is require_once method used to include unconditional class or library file?
  - [ ] Is include_once method used to include conditional class or library file?
  - [ ] Does all project “includes” have fully qualified path?



# Naming Conventions
  - [ ] Is Class name in camel case format?
  - [ ] Is Class name descriptive and easy to understand?
  - [ ] Are all Constants defined in config.inc.php file?
  - [ ] Are all Constants in uppercase with underscores to separate words?
  - [ ] Are Constants using prefix of Class/Package they are used in?
  - [ ] Are true, false and all null constants in lowercase?
  - [ ] When accessing pre defined variables like form elements, session variables, cookies, environment variables, global variables etc , is code using super global variable?
  - [ ] Are all characters in filename with lowercase?
  - [ ] Are class files having “class.inc” extension?
  - [ ] Are include files having “inc.php” extension?
  - [ ] Is file name under 32 chars?



# General Coding Standards
  - [ ] Is Title, keyword and description add to meta tag for all the publicly accessible pages?
  - [ ] Does image and anchor tag has title and alt attribute?
  - [ ] Is project maintaining and using configuration path variable?

# Architecture
  - [ ] Design patterns if used are correctly applied
  - [ ] [Law of Demeter](https://en.wikipedia.org/wiki/Law_of_Demeter) is not violated
  - [ ] A class should have only a single responsibility (i.e. only one potential change in the software's specification should be able to affect the specification of the class)
  - [ ] Classes, modules, functions, etc. should be open for extension, but closed for modification
  - [ ] Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program
  - [ ] Many client-specific interfaces are better than one general-purpose interface.
  - [ ] Depend upon Abstractions. Do not depend upon concretions.

# API
  - [ ] APIs and other public contracts check input values and fail fast
  - [ ] API checks for correct oauth scope / user permissions
  - [ ] Any API change should be reflected in the API documentation
  - [ ] APIs return correct status codes in responses

# Logging
  - [ ] Logging should be easily discoverable
  - [ ] Required logs are present
  - [ ] Frivolous logs are absent
  - [ ] Debugging code is absent
  - [ ] No `print_r`, `var_dump` or similar calls exist
  - [ ] No stack traces are printed
  
# Documentation
  - [ ] Comments should indicate WHY rather that WHAT the code is doing
  - [ ] All methods are commented in clear language.
  - [ ] Comments exist and describe rationale or reasons for decisions in code
  - [ ] All public methods/interfaces/contracts are commented describing usage
  - [ ] All edge cases are described in comments
  - [ ] All unusual behaviour or edge case handling is commented
  - [ ] Data structures and units of measurement are explained


# Security
  - [ ] All data inputs are checked (for the correct type, length/size, format, and range)
  - [ ] Invalid parameter values handled such that exceptions are not thrown
  - [ ] No sensitive information is logged or visible in a stacktrace
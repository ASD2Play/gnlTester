# gnlTester (2019+)

Tester for the 42 school's get_next_line project (with custom leak checking on Mac, using valgrind on Linux).

Clone this tester into your get_next_line repository.  
(Works on Linux and Mac, handles SIGSEGV for all tests and timeout for the mandatory part.)

# Commands
- `make m` = run mandatory tests  
- `make b` = run bonus tests  
- `make a` = run mandatory + bonus tests  

- `make dockerm` = run mandatory tests in the Linux container  
- `make dockerb` = run bonus tests in the Linux container  
- `make dockera` = run mandatory + bonus tests in the Linux container  

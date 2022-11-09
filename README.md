# hometask-project-set-up

## Requirements  
Clone this repository to your workstation.  
No other file or code modifications expected.  

## Tests
Run `yarn install` to install all dependencies. 
Run `yarn test` to check test command output.  
  
The concole output will show you the result.


## Test console output example

❯ yarn test
yarn run v1.22.19
$ jest
 PASS  tests/rect.test.js
  Calculating Perimeter and Area, checking valid and invalid inputs
    ✓ calculates the Perimeter of rectangle with valid inputs (2 ms)
    ✓ checks the the invalid inputs for perimeter function (1 ms)
    ✓ calculates the Area of rectangle with valid inputs
    ✓ checks the invalid inputs for area function (2 ms)
    ✓ console message with perimeter and area values (1 ms)
    ✓ console message with perimeter and area values (1 ms)
    ✓ console message for invalid inputs (2 ms)

Test Suites: 1 passed, 1 total
Tests:       7 passed, 7 total
Snapshots:   0 total
Time:        1.335 s, estimated 2 s
Ran all test suites.
✨  Done in 3.43s.
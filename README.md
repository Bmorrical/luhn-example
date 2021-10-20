# MODE Transportation Developer Interview Exercises

## Instructions

1. Fork this repository to your GitHub account.
1. Clone the forked repository to your local machine.
1. Create a new branch titled `interview/<your first name>-<your last name>` off of the repo's `master` branch.
1. Complete the exercises in both the "backend" and "frontend" folders.
1. Push your branch to your fork and create a new pull request on the main interview repository for your work
1. Tag your interviewer(s) as the reviewer(s).
1. Your code will be reviewed and you will then be given instructions re. the next steps in the interview process.

If you have any questions, please don't hesitate to get in touch - happy coding!


# Luhn Number Validator
Written for php version 7.1.

### Usage
To use the LuhnValidator, run this command from the command line:
```
php src/main.php <number>
```
The current working directory doesn't matter. The number provided will be validated against the Luhn checksum. The number must be a single, whole number of at least 2 digits.

### Tests
To run automated tests, execute this command:
```
php test/luhn-test.php
```
This will run a series of tests against the LuhnValidator class and then again against the main.php script. Output simply echoes out Pass or FAIL messages.

# Report for Assignment 1 resit

## Project chosen

Name: Codecov-Python

URL: https://github.com/codecov/codecov-python

Number of lines of code and the tool used to count it: 1900 lines of code, using lizard

Programming language: Python

## Coverage measurement with existing tool

The name of the existing tool that was used is "coverage" for python and it has been used with the unnitest discover function for the tests folder inside the project.

![51% initial coverage report](<Screenshot 2024-07-10 133025.png>)

## Coverage improvement

### Individual tests

<The following is supposed to be repeated for each function (2 in total)>

<Function 1> - (def write)

![added code](image.png)

![initial test](<Screenshot 2024-07-11 055058.png>)

![fianl completed branch result](<Screenshot 2024-07-11 062004.png>)

<State the coverage improvement with a number and elaborate on why the coverage is improved>

The coverage improvement for the whole project has grown with 2% after this enhacement, and the coverage is improved because it takes into consideration a few cases the initial branch testing did not account for such as the "https//: starting cases" or the non matching colored texts(as seen in coverage.xml screenshot)

<Function 2> - (remove_non_ascii/_add_env_if_not_empty)

![added code](image-1.png)

![initial test](<Screenshot 2024-07-11 063630.png>)

![final completed branch results](<Screenshot 2024-07-11 064832.png>)

<State the coverage improvement with a number and elaborate on why the coverage is improved>

The coverage improvement for the whole project has grown with 2% after this enhacement, and the coverage is improved because it takes into consideration the cases for the 2 functions in question which were not tested during the branch testing done(as seen in coverage.xml screenshot)

### Overall

![initial 51%](<Screenshot 2024-07-10 133025-1.png>)

![final 55%](<Screenshot 2024-07-11 064736.png>)

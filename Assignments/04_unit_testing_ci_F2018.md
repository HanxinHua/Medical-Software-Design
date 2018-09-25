# Unit Testing + Continuous Integration

In this assignment you will write and test several python modules. You will also need to configure Continuous Integration (CI) to automatically run tests on push and pull request events. 

When setting up Travis CI, ensure that your repository is "turned on" in the travis control panel for the BME organization [here](https://travis-ci.org/profile/Duke-BME-Design).

## Fruit comparison
Building on the example seen in the [lecture notes](Lectures/UnitTestingCI.md), write a function called `is_apple` in a file called `fruit.py`. `is_apple` must take a candidate string and return `True` if it represented an apple and `False` if it did not represent an apple. Then write robust unit tests for this fruit comparator. Try to be as comprehensive as possible with your unit tests (e.g. testing for accidental case mismatches, etc). You must use `@pytest.mark.parametrize` for at least one test.

## 

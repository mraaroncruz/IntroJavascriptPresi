# What I will cover

- What are tests?
- Why would I want to test?
- What are the common ways to test?
- What is TDD?
- Why should I care?
- Explanation of TDD process



# What are software tests?

### Here is some code

    function addTwo (n) {
      return n + 2;
    }



### And some tests
#### In their most basic form

    function addTwo (n) {
      return n + 2;
    }

    console.log(addTwo(4) + " should equal 6")
    console.log(addTwo(6) + " should equal 8")

Getting feedback and being able to test edge cases

    console.log(addTwo(null) + " should equal ?")
    console.log(addTwo("") +   " should equal ?")

### So we can be confident our code functions like we expect


## Next step, make it more readable and repeatable with assertions

    function assert (assertion, message) {
      message = message || ""
      if(!assertion) {
        console.log("FAIL: " + message);
      } else {
        console.log("PASS");
      }
    }

    assert(addTwo(6) === 8)
    //= "PASS"

And more expressive

    function assertEqual(example, other, message) {
      assert(example === other, message);
    }

    function assertMatches (exampe, other, message) {
      assert(example.match(other), message);
    }

    assertEqual(addTwo(2), 3, addTwo(2) + " does not equal 3");
    //= "FAIL: 4 does not equal 3"

Definition **Test Suite**:
A collection of tests that belong to a certain project/feature
Should be run often when changes are made to the codebase


## 3 main approaches to testing

## No tests

## Test after

## Test before === TDD



# Unit Testing

For testing we will be using XUnit, has testing framework. Has a short learning curve, is intuitive and flexible. There are other libraries that we will use to turn the test semantic and focus more easier.
**Moq**

Moq, is a library that allow us to create mock of an object, without having to implement the object it self. The focus of the test the code that we develop, and not the dependencies of that code. Moq creates this abstraction of the dependencies.

**Shouldly**

Shouldly, is fluent assertion library. It allow us to fluently assert our tests, without having to think a lot about it.

**coverlet**

coverlet, is a code coverage library. Will verify if our production code is cover my the tests. It is important to exclude the tests code from the coverage :) .

## Create Unit Tests
Naming conventions are very important, specially when we have to fix bugs or maintain the solution in the future. It is a sanity check.

By convention, the test project have the same name has the production project name, with the suffix **Tests**.

1. In Jest, what are the differences between describe() and it() globals, and what are good uses for them?

    describe creates a block that groups together several related tests in one test suite, this therefore shortens the code and reduces chances of errors and bugs, it is the unit test itself which are great if you only want to test a certain bit of code, it should be noted that multiple it 'tests' are grouped into a describe but you can also just have one it test if preferential

2. What is the point of Test Driven Development? What do you think about this approach?

    the point of TDD is to utilize repetition of short development cycles to create tests that fail at first then pass then you refactor them thereafter, this approach is great to design the test and also to help prevent future errors and regressions to a former state

3. Mention three types of automated tests.

    There are unit tests to test small units of code i.e functions/methods, integration tests are used to test several units of code i.e endpoints and end-to-end tests are used to test the whole application as a whole, but these are not often used as they can be expensive and slow. Therefore the more affordable approach to testing an application is by having multiple unit and integration tests
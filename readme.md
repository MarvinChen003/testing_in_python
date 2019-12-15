## What is Software Testing
1. Testing is the process of exercising or evaluating a System or system component by manual or automated means to verify that it **satisfies specified requirements**
2. Software Testing is a structured process that **uncovers the defects** in a software product. Software Testing is destructive in nature (dismantling the wishful assumption the code is bug-free) while the other tasks in the project are constructive
3. Testing is a process of executing a program with the intent of **finding errors**

**In simple:**
1. Satisfy requirements
2. Uncover defects
3. Find error

## Testing Types
Functional
- [x]  Unit
- [ ]  Regression
- [x]  Integration
- [ ]  System
- [ ]  UAT

Non Functional
- [ ]  Performance
- [ ]  Stress
- [ ]  Security

## Why testing is important
- Hard to catch the bug without unit tests

![Alt Text](http://5b0988e595225.cdn.sohucs.com/images/20190415/c457f570b60b47e3bf6442966cfbfe8c.gif) 

- Easy crash without integration tests

![Alt Text](http://5b0988e595225.cdn.sohucs.com/images/20190415/de0d3ed316da43988afbc7b32e82c674.gif)

- Production go live without testing

![Alt Text](http://5b0988e595225.cdn.sohucs.com/images/20190415/78091c068ae848e2ae16e768a1e0a103.gif)


- The basement of CICD is testing
- 70% time are used for writing tests 30% for the scripts when coding in cloud team 
- Testing is a major subject to learn when we transforming from scripting to engineering

## Testing in python

**python keyword assert**
```bash
python built_in_assert_test.py
```

**test runners**

1. **doctest** - prepackaged with Python

    ```bash
    python -m doctest -v doctest_test.py
    ```
2. **unittest** - The unittest (standard module) test framework is python’s xUnit style framework.
    
    ```bash
    python unittest_test.py
    ```
3. **pytest** This is really where testing gets fun.
- No boilerplate, no required api
- We can use Python’s built in assert statement
    ```bash
    pytest unittest_test.py
    ```

## Why pytest
- Support doctest, unittest 
- Support for the built-in assert statement
- Ability to rerun from the last failing test
- An ecosystem of hundreds of plugins to extend the functionality


## Advanced topics
- unittest setUp, tearDown VS pytest fixtures
- test strategy (Given-When-Then)
- TDD
- Mock, MagicMock, patch


## reference docs：
- https://realpython.com/python-testing/
- https://pythontesting.net/start-here/
- https://docs.pytest.org/en/latest/